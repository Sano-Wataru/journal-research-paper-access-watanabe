# 論文圧縮：セクション別 省略内容と理由

10ページ→8ページ以内への圧縮作業において、各セクションで省略・短縮した内容とその理由をまとめる。

## 共通方針

- **冗長・重複**（同趣旨の繰り返し、Abstract / Introduction / Conclusion の重複）を優先して削る
- **段階的な手順説明**を、パラメータと結果が分かる要約に置き換える
- **本論の貢献に直結しない補足例**（背景の具体システム、モデル個別の長い解説）を削る
- 文体を **受動態・短文化**し、`\deleted` / `\revised` / `deletedblock` で差分を保持

---

## Abstract

| 省略した内容 | 理由 |
|---|---|
| 「prior work に残された課題」という修飾 | 提案の核心説明に不要な前置き |
| 前処理（trimming, calibration, feature estimation 等）と分類を別文で述べていた部分 | 1文に統合して Abstract の行数を削減 |
| 評価実験の詳細（複数条件、学習、精度・混同行列の報告）を複数文で展開していた部分 | 実験の細目は本文に任せ、Abstract は概要のみに限定 |
| 「結果が前処理の組合せでどう機能するかを示す」という解釈文 | Evaluation セクションと重複 |

---

## Introduction

### 第1段落（背景）

| 省略した内容 | 理由 |
|---|---|
| オフィス活動認識の具体例2件（fuzzy FSM `\cite{6891825}`、職場センサと生産性 `\cite{7106905}`）とその補足1文 | 冒頭の `officemonitoring1`–`6` で背景は示済み。本論（点群＋手元分類）への橋渡しとして遠い |
| レポート機能列挙文の冗長表現（indicates / include → lists） | 同内容の言い換えのみで情報量が増えない |

### 第2段落（課題設定）

| 省略した内容 | 理由 |
|---|---|
| 「時系列活動の記録」「粗大姿勢だけでは不十分」「手元分類が必要」を3文に分けていた部分 | 2文に統合。論点は維持 |
| デスクワークの中心性、手を伴う動作、粗大姿勢では区別できない旨の段階説明 | 要約文1文で代替可能 |
| 手元分類の有用性（タスク切替・実作業時間）を箇条書き的に展開していた部分 | 1文に圧縮 |

### 第3段落（先行研究）

| 省略した内容 | 理由 |
|---|---|
| Katayama 系の詳細（小型 LiDAR、2D-CNN、被験者1名）を複数文で述べていた部分 | 引用は残し、限界（1名評価）だけ要約 |
| Glandon 系の詳細（シルエット→関節→分類、LiDAR 使用の曖昧さ） | 同上。手法の細部は Related Works / 本文と重複しうる |
| 先行研究の弱点を2文（手元分類不可＋多点群・複数人モデル不足）で述べていた部分 | 1文に統合 |

### 第4段落（提案・評価概要）

| 省略した内容 | 理由 |
|---|---|
| 「In light of the background, we propose」等の導入句 | 受動態・短文化 |
| 取得・保存・分類の手順を複数文で述べていた部分 | 1文に統合 |
| 評価実験（複数 LiDAR、前処理、条件変化、学習、精度評価）の長い説明 | Experiment setup / Evaluation と重複 |
| 評価指標と混同行列の目的説明を別文にしていた部分 | 1文に統合 |
| **論文構成の説明段落全体**（Section 2–6 の案内） | IEEE 論文では一般的に省略可。ページ削減効果が大きい |

---

## Related Works

### Model architecture（旧全文 → `deletedblock`）

| 省略した内容 | 理由 |
|---|---|
| 分類の定義段落 | 要約文1文に圧縮 |
| voxelization → PointNet の段階的な長文説明（MLP、max pooling、置換不変性の個別文） | モデル列挙の要約で十分 |
| PointCNN / ShellNet / A-CNN / SO-Net / Kd-network の**モデルごとの個別段落**（X-Conv、ShellConv、環状畳み込み、SOM `\cite{58325}`、kd-tree 等） | 各モデルの技術詳細は本論の提案手法に直接使わない。Survey 的説明として過長 |
| 既存研究の2分類（enumerate）と本研究との差分の長い段落 | 2文の要約に置換 |

### Improvement for object detection（旧全文 → `deletedblock`）

| 省略した内容 | 理由 |
|---|---|
| 点特徴の概要・利用方法の導入2段落 | 1文に圧縮 |
| 固有値特徴（entropy、omnivariance）の意味説明 | 引用と名称列挙で足りる |
| Lv et al. の凸包記述子の手法詳細、4特徴比較の記述 | 本論は別の4特徴（normals 等）を使用 |
| SHOT / POD の個別説明（DM、3D shape search 等） | 名称と引用の列挙に圧縮 |

---

## Proposed system — System model

| 省略した内容 | 理由 |
|---|---|
| sensor device / edge computer / GPU server の**各コンポーネントを別文で紹介**していた部分 | 1文に統合。Fig.~\ref{system} と重複 |
| データフロー全手順（取得→保存→受信→マージ→trimming→特徴→クラスタリング→ダウンサンプリング→正規化→分類）の**11文の逐次説明** | Methodology と内容重複。1文のパイプライン要約で代替 |

---

## Proposed system — Methodology

### 旧全文（`deletedblock` 内）

| 省略した内容 | 理由 |
|---|---|
| キャリブレーションの回転・並進の段階説明 | 要約文で十分 |
| トリミングの手動頂点指定、固定席オフィスの前提の詳述 | 実験設定と重複 |
| raw point cloud 図（`rawdata.png`）への言及・図自体 | trimmed 図で十分 |
| 各特徴（normals / dimensionality / proportion / FPFH）ごとの **KNN→共分散→計算** の繰り返し説明 | 同構造の繰り返し。KNN パラメータは1箇所に集約 |
| FPFH の Darboux frame 3変数の数式レベル説明 | 実装は Open3D 依存。式より処理概要で足りる |
| DBSCAN の core / reachable / outlier の定義、k-means の反復手順 | アルゴリズムの教科書的説明。パラメータ値が実験に必要な情報 |
| 正規化（重心から最遠点まで距離1.0）の詳述 | 1文要約 |
| PointNet++ の2回繰り返し処理の詳細文 | 1文要約 |

### 有効本文（`\revised`）で残したもの

- 引用、数式（dimensionality / proportion）、パラメータ値、Fig.~\ref{trimdata} / Fig.~\ref{features} は維持

---

## Experiment setup

### Experimental system

| 省略した内容 | 理由 |
|---|---|
| 「We developed」→ 受動態への言い換え | 文体統一 |
| 機器列挙の冗長表現（two sets of … units 等） | 同情報を短く記述。Table~\ref{experiment} が詳細を保持 |

### LiDAR deployment

| 省略した内容 | 理由 |
|---|---|
| センサ配置を3文（向き合い、1.0 m、10°、PC 位置）で述べていた部分 | 1文に統合。Fig.~\ref{jlidar} が補足 |

### Training data acquisition

| 省略した内容 | 理由 |
|---|---|
| 4クラスごとの取得手順を個別に繰り返す長文（各クラスに時間・繰り返し・subfigure 参照） | 4クラス共通パターンの繰り返し。3文＋Fig.~\ref{labels} に集約 |
| 倫理審査承認の footnote（`deletedblock` 内） | 圧縮の副作用。**投稿用では非表示になる**ため、必要なら `\revised` 側へ移す判断が必要 |

### Test data acquisition

| 省略した内容 | 理由 |
|---|---|
| 4クラスごとの取得手順の繰り返し長文 | Table~\ref{testacquisition} に集約（情報は保持、記述形式を変更） |

### Processing of proposed system

| 省略した内容 | 理由 |
|---|---|
| Methodology 参照の冗長文 | 短文化 |
| Open3D による法線・共分散・FPFH 計算の個別説明 | 1文に統合 |
| DBSCAN / k-means の「outliers and clusters removed」の段階説明 | 1文に統合 |
| PointCutMix の手順詳細（3点群準備、β分布、最近傍マッチ、上位 λ% 置換を A–B / A–C で2回） | アルゴリズムの細部。1文要約で実験再現の要点は残す |
| 学習/検証 4:1 分割、MSG、学習後パラメータ保存の冗長表現 | 短文化 |

### Evaluation metric

| 省略した内容 | 理由 |
|---|---|
| 精度式の変数説明を長文（actually indicate … 等）で述べていた部分 | 数式は維持し、変数定義のみ短縮 |

---

## Evaluation

### セクション構成

| 省略した内容 | 理由 |
|---|---|
| **Confusion matrices サブセクション全体**（`main.tex` でコメントアウト） | ページ削減。混同行列の考察は Conclusion 要約文に残す |

### Validation results

| 省略した内容 | 理由 |
|---|---|
| 図の読み方説明（3本の折れ線＝クラスタリング3条件）を2文で述べていた部分 | 1文に統合 |
| 4特徴それぞれについて「accuracy nearly 100%」と繰り返す4段落 | 4回の同型記述。1文に統合 |
| early stopping 条件の冗長文 | 短文化 |

### Accuracy

| 省略した内容 | 理由 |
|---|---|
| 表の紹介、被験者範囲、25% ベースライン、全ケース超過、クラスタリング比較、特徴比較を**6文**で述べていた部分 | 同趣旨の解釈を3文に圧縮。Table~\ref{accresults} が数値を保持 |

---

## Conclusion

| 省略した内容 | 理由 |
|---|---|
| 提案の新規性・優位性を3文（fine movements、shape features に着目したモデル等）で展開していた部分 | Introduction / Proposed system と重複 |
| 評価全体の長い再掲（データ取得、前処理、条件変化、学習、指標、混同行列の目的） | Experiment / Evaluation と重複 |
| validation 精度の比較と所見（クラスタリング差）の詳述 | Evaluation 要約で代替 |
| test 精度の安定性・変動、normals / dimensionality features の詳細所見 | 3文に圧縮 |
| 混同行列の代表ケース比較（高精度 normals 無 clustering vs 低精度 k-means、typing–pad 混同の双方向説明）の長文 | 主要所見のみ4文に圧縮 |

---

## 参考文献から外れた引用（3件）

| BibTeXキー | 文献 | 落ちた経緯 |
|---|---|---|
| `6891825` | Langensiepen et al., FUZZ-IEEE 2014 | Introduction の具体例段落を `deletedblock` に移動 |
| `7106905` | van der Valk et al., ISSNIP 2015 | 同上 |
| `58325` | Kohonen, *Proceedings of the IEEE* 1990（SOM 原典） | Related Works 要約化に伴い、SO-Net の `\cite{Li_2018_CVPR}` のみ残した |

---

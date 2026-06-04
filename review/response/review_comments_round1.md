Dear Mx. SANO:

I am writing to you regarding manuscript # Access-2025-38261 entitled "Classification of postures of people with hand movement working in office environment by LiDAR sensor network" which you submitted to IEEE Access.

Your article was peer reviewed with interest but has not been recommended for publication in its current form.  We strongly encourage you to address the reviewers’ concerns, which can be found at the bottom of this letter, and resubmit your article to IEEE Access once you have updated it accordingly.
 
Please note that IEEE Access has a binary peer review process. Therefore, to uphold quality to IEEE standards, an article is rejected even if it requires minor edits.
 
When updating your manuscript, you should elaborate on your points and clarify with references, examples, data, etc. If you disagree with any technical points the reviewers have made, please include your counterarguments in your response to the reviewers (more information detailed below) and work this into the updated manuscript. 

Also, note that if a reviewer suggested references, you should only add those that are relevant to your work if you feel they strengthen your article. Recommending references to specific publications is not appropriate for reviewers and you should report excessive cases to ieeeaccessEIC@ieee.org.  Authors are not obligated to cite articles that are recommended by the reviewers, and the final decision on the article will not be influenced by whether or not authors cite these suggested references.
 
IEEE Access allows one opportunity to resubmit. If the updated manuscript is determined not to have addressed all of the previous reviewers’ concerns, or if the Associate Editor still has substantial technical concerns, the article will be rejected and no further resubmissions will be allowed.
 
When you are ready to resubmit your updated article, you can do so in the IEEE Author Portal.  When you log into the IEEE Author Portal you will see the title of the rejected article and the option to “Start Resubmission”.  
 
Upon resubmission you will be asked to upload the following 3 files:

1) A document containing your response to reviewers from the previous peer review.  The “response to reviewers” document (template attached) should have the following regarding each comment: a) Reviewer’s concern, b) your response to the concern, c) your action to remedy the concern. The document should be uploaded with your manuscript files under "Author's Response Files.”

2) Your updated manuscript with all your individual changes highlighted, including grammatical changes (e.g. preferably with the yellow highlight tool within the pdf file). This file should be uploaded with your manuscript files as “Highlighted PDF.”

3) A clean copy of the final manuscript (without highlighted changes) submitted as a Word or LaTeX file, and as a PDF, both submitted as the “Main Manuscript.”

**IMPORTANT: Please see the attached Resubmission Checklist that details all the items listed above.  Please utilize this checklist to ensure you have made the necessary edits to your manuscript, and to ensure you have all the necessary files prepared prior to resubmission.

*** AUTHOR LIST CHANGES: If your revised manuscript has an updated author list, you will need to submit a formal request to the Editor by completing the attachment labelled ‘Request for Byline Change,’ and uploading it as 'Request for byline change form.' This should include a DETAILED justification explaining each author’s contribution(s) to the work. You will also need to provide the justification for the author change during the submission process.  Change in the author list is considered rare and exceptional, and the decision to allow such changes rests with the Editor. Once the list and order of authors has been established, the list and order of authors should not be altered without permission of all living authors of that article.

We sincerely hope you will update your manuscript and resubmit soon. Please contact me if you have any questions.

Thank you for your interest in IEEE Access.

Sincerely,

Dr. Salvatore Surdo
Associate Editor, IEEE Access
surdo.salvatore@gmail.com

Reviewers' Comments to Author:

Reviewer: 1

Comments:
After reviewing this article, unfortunately this has to be rejected and not re-submitted due to the below reasons despite the references listed and further scope provided. May be this can be classified for other types of article(topic review etc.) submissions that IEEE Access offers.

C.1-1
-Lack of motivation behind the article and too descriptive
[原因]
なぜ姿勢や手の動きの分類が、「オフィス効率モニタリング」において重要な課題であるか、という結びつきが弱い。
以下の背景、先行研究ではこの結びつきを示せていない。

1節「Introduction」 1段落
"The office-efficiency…on mobile and web applications."
背景：一般的な関心の提示（オフィス効率モニタリングが注目されていること、及び既存システム）。

1節「Introduction」 2段落
"The weakness of the prior works…to handle multiple people."
先行研究：先行研究が手の動きの違いを識別できない、複数人を扱えないことを弱点として挙げている。

[修正案]
1節「Introduction」1段落末尾（オフィス効率モニタリングへの関心、既存システムの紹介の直後）に以下を追加。
・オフィス効率モニタリングで実際に推定・記録したいもの（論文で扱う範囲に合わせて限定）
・机上の粗い姿勢や在席だけでは不十分な理由
・手元の分類が区別したいものの何に有効なのか

1節「Introduction」2段落目冒頭に以下を追加。
1段落目で述べた区別したいもののために、どの点で既存研究が不足しているかを述べる。

また、どのような結果を得るのか。その結果に対して、統計検定 (C.2-15) によって有意差を示すことを述べ、研究の実証を行うことを明示する。

C.1-2
-Lack of novelty in the manuscript despite the article suggesting otherwise and mostly contained cited ones that were novel
[原因]
提案の新規性が明確になっていない。

以下の要素を述べているが、どれが新規性の中心かわからない。提案の中心とそれぞれ並列に記述されてしまっている。
・手の動きの分類：提案の中心 (1節3段落 …that classifies the postures of people with hand movement in an office by using a LiDAR sensor network. )
・多人数対応：オフィスモニタリングにおいて必要な要件 (1節2段落 …as well as to handle multiple people.)
・エッジコンピューティング：既存の要素技術 (1節3段落 we propose an edge computing system…)
・複雑な前処理パイプライン：方法論 (1節3段落 We performed 
preprocessing, i.e., trimming, feature estimation, clustering, and normalization…)

実環境の課題＝＞手の動きの分類の必要性＝＞提案手法
このロジックを強化する必要がある。

[原因（指摘）]
Lack of novelty と指摘されているので、貢献、独創性ではなく、新規性が明確になっていないという意味です。

手の動きを認識したいことを目的としている割に、そのための新規の提案がなく、従来の手法を組み合わせて用いていると言われています。なので、上のコメントで、May be this can be classified for other types of article(topic review etc.  つまり既存研究のreview 論文が適切でないか？と言われています。

> 手の動きの分類の必要性＝＞提案手法
> このロジックを強化する必要がある。
これはおっしゃるとおりです。

[修正案]
C.1-1同様。
オフィス効率モニタリングの観点での実環境の課題＝＞手の動きの分類の必要性＝＞提案手法の流れが作れている。
「1段落目で述べた区別したいもののために、どの点で既存研究が不足しているかを述べる。」
目的のために既存研究では行われていないことを明示しているため、本研究の新規性も明確になっている。

結果→統計検定→有意差の流れを明示する。

C.1-3
-Parts of the article are vague particularly in the discussion area with minimal presence of any form of visualizations
[原因]
・結果の解釈不足
　5節 B. Accuracy ( In all cases from Tables 2(a) through 2(l), the accuracy significantly exceeded this baseline…)
　・分類精度が上がった/下がったという事実の羅列だけでなく、結果に対する考察が必要。
　・なぜこの特徴量が手の動きの分類に効果的だったのかに対する説明の不足。

・誤分類 (misclassification) の原因の分析不足
　5節 C. Confusion matrices (However, there were frequent misclassifications of typing as pad operation…)
　原因はデータの特徴にあるのか、モデルにあるのか、環境にあるのかに対する説明の不足。

・限界の議論不足
　データセットの小ささや、静的な環境でのみ評価したことに対する説明の不足。

・すべての結果が示されていない
　5節 B. Accuracy, C. Confusion matrices
　table 2において、精度評価の結果が12条件すべて示されている一方で、table 3, table 4の混同行列の結果は2条件のみが示されている。
　結論においてdimensionality featuresの結果が最も高い精度を示したとあるが、その混同行列は表で示されていない。(6節 3段落 …the dimensionality features resulted in the higher accuracies…)

[原因（指摘）]
vague particularly in the discussion area という指摘については、discussion (考察) の要点をまとめてリストするなどして欲しいということかもしれません。

with minimal presence of any form of visualizations は示した結果が多すぎるということかも。結果を山ほど見せるのではなく、要点を整理して示して欲しいということかもしれません。

[修正案]
5節「Evaluation」subsection「Accuracy」段落末尾
「なぜその特徴が効く/効きにくいか」の解釈を追記する。以下の二つの傾向について、その解釈を追記。
・no clustering or DBSCAN achieved higher accuracy than K-means.
・normals yielded higher accuracy when no clustering or DBSCAN was employed.

5節「Evaluation」subsection「Confusion matrices」段落末尾
以下の軸で誤分類に対する分析を追記する。
・データ表現（特徴）: その特徴では二クラスが特徴空間で近い、など
・モデル（分類器・クラスタリング）: 過学習、クラスタの分割の仕方、など
・環境・センサ: 配置・見え方・ノイズで手の区別がつきにくい、など
既存の以下の文は「環境・センサ」の分析として残す。
This is likely due to the difficulty in distinguishing whether both
hands were touching the pad or the keyboard

5節「Evaluation」Table
Table 3, Table 4の混同行列については、Table 2のAccuracyの結果同様に、すべての条件に対応する結果を示す。ただし、混同行列の値では結果の量が多くなりすぎるため、Precision, RecallをAccuracyとともに示す。

上記の考察の要点を、リスト形式で示す。


6節「Conclusion」末尾　新設段落
Limitations としてデータ規模・静的条件などの限界を明記する。

C.1-4
-Certain portions of article are more theoretical and lengthy in general
[原因]
・既知の技術の冗長な説明 (2節 2～4段落 Qi et al. presented a network called PointNet…,  Li et al. presented PointCNN…,  Li et al. proposed a method called SONet…)
・手法セクションにおける本研究独自の工夫の記述漏れ。 (3節 B. Methodology 4～段落 Normals. We implement the k-nearest neighbor algorithm (KNN) …)



既知の技術の冗長な説明
・Related works　
　モデルの詳細すぎる説明（PointNet++, PointCNN, ShellNet…）。本研究の位置づけのための説明ではなく、関連研究の手法の説明になってしまっている。
・Methodology
　以下の既知の技術の説明において、導出の手順や、式展開まで行っている。一方で本研究の独自の工夫が抜けている。
　・既知の特徴量（Normals, Dimensionality feature, Proportion of variance, FPFH）
　　具体的に設定したパラメータ値の記述がない。PCAにおいて、どの次元まで削減したか説明がない。
　・既知のクラスタリング手法（DBSCAN, k-means）
　　　

[修正案]
2節「Related works」2～4段落目
以下の既知の技術の説明は詳細すぎるため、短く要約する。
・PointNet（「PointNet transforms... MLP... max pooling...」の詳細）
・PointCNN（「X-Conv... X-transformation... weight and permute...」の詳細）
・ShellNet（「ShellConv... origin... shells... max pooling...」の詳細）
・A-CNN（「annular convolutions... plane... convolution...」の詳細）
・SO-Net（「SOM... overlap of receptive fields... kNN...」の詳細）

既存研究の本研究との差分・位置づけを末尾に追記する。

3節「Proposed system」subsection「Methodology」4段落目以降
以下の既存手法について、パラメータを明示する。
・PCA
　"We use PCA to reduce the dimensions of the FPFH."の直後に記述。
・kNN
　"We implement the k-nearest neighbor algorithm (KNN) using the parameters we determined."の直後に記述。
・DBSCAN
　"We use DBSCAN to determine the parameters for DBSCAN ..."の直後に記述。
・k-means
　"e use k-means to determine the number of clusters for k-means ... "の直後に記述。

Additional Questions:
Please confirm that you have reviewed all relevant files, including supplementary files and any author response files, which can be found in the "View Author's Response" link above (author responses will only appear for resubmissions): Yes, all files have been reviewed

1) Does the paper contribute to the body of knowledge?: No

2) Is the paper technically sound?: No

3) Is the subject matter presented in a comprehensive manner?: No

4) Are the references provided applicable and sufficient?: No

5) Are there references that are not appropriate for the topic being discussed?: No

5a) If yes, then please indicate which references should be removed.:


Reviewer: 2

Comments:

C.2-1
1.The paper’s methodology relies on a very limited number of participants: only three for training and nine for testing. This small sample size undermines the statistical power and generalizability of the study's results. 
[原因]
・訓練データの被験者数の少なさ
　4節 C. Data acquisition 1) Training data acquisition 6段落目 “The three subjects in this study are denoted as subjects A, B and C,”
・テストデータの被験者数の少なさ
　4節 C. Data acquisition 2) Test data acquisition 6段落目 “The nine subjects in this study are denoted as subjects A to I.”

[修正案]
データの追加取得を行い、テストのサンプル数を20名に増やす。
4節「Experiment setup」subsection「Experimental system」末尾 C.2-2追記部分
追加取得後の被験者の記述に修正。
4節「Experiment setup」subsection「Test data acquisition」6段落目
テストのサンプル数を20名に修正

4節「Experiment setup」subsection「Processing of proposed system」
加えて、学習データ同様、データ拡張によって、10～20名仮想データを増やす。
訓練データ、テストデータともに何名にデータを拡張したか明示する。

C.2-2
A broader sample including more subjects from varied backgrounds is necessary to make findings applicable to typical office settings. The absence of demographic reporting further limits the scope and relevance. Consequently, overall conclusions may not reliably extend to diverse populations.​
[原因]
・被験者の属性情報の欠如
　5節 C. Data acquisition
　セクション全体で、「被験者A〜I」というラベルづけしかされていない。
　多様な層の被験者が含まれているかどうかが分からない。
　被験者の性別、年齢層、体格（身長・腕の長さなど）

[修正案]
4節「Experiment setup」subsection「Experimental system」
末尾に被験者数とその属性を追記する。
分類対象の動作がタイピングなどPC操作のため、国籍や年齢といった属性によらないという説明を追記する。

C.2-3
2. The rationale for choosing between DBSCAN, k-means, or no clustering is inadequately discussed. The criteria guiding these methodological choices are not transparent, 
[原因]
・手法選択の動機の欠如
　3節 B. Methodology 8～10段落目
　ノイズ除去のためにDBSCANとk-meansを使用したという目的のみが記述されており、根拠が示されていない。

[修正案]
3節「Proposed system」subsection「Methodology」9～10段落目
"We use DBSCAN ... in the point cloud on the basis of the parameters [35]"
"We use k-means to determine the number of clusters for k-means so as to remove noise in the point cloud [36]."
それぞれの直後に、このクラスタリング手法を採用した根拠を提示する。
また、クラスタリングなしを実施することを明示し、クラスタリングの有無で結果がどう変わるか定量評価するための基準であることを明示する。

根拠は既存文献を引用する。クラスタリング手法のレビュー文献と、k-meansとDBSCANそれぞれの代表的文献（可能であれば原典）を引用し、k-meansとDBSCANが一般的に用いられている手法であることを示す。

C.2-4
and there is no comparison with alternative clustering methods or parameter tuning strategies. Without evidence or literature support for the selection process, reproducibility suffers.
[原因]
3節「Proposed system」 subsection「Methodology」9～10段落目 "We use DBSCAN to determine the parameters for DBSCAN…"
　パラメータを決定したという記述はあるが、具体的な数値が記載されていない。
　
　DBSCANとk-meansの元論文 [35][36] の引用はされているが、それを用いる根拠となる文献が引用されていない。選択の妥当性が示せていない。

上記のパラメータ・手法を用いる根拠が示されておらず、再現性を損なっていると判断された。

[修正案]
3節「Proposed system」subsection「Methodology」9～10段落目
C.2-3において引用したレビュー文献に含まれる、DBSCANとk-means以外の手法についても実施して比較を行う。

複数のパラメータ最適化手法の結果を求め、比較する（グリッドサーチ・ランダムサーチ・ベイズ最適化等）

グリッドサーチによりパラメータを最適化する。これを根拠とする。また各手法の最適パラメータとともに、パラメータ最適化手法自体の、パラメータも示す。

C.2-5
More thorough explanations and comparative analyses are required. The current approach leaves readers unclear about how clustering impacts classification results.​
[原因]
・クラスタリングが分類結果に与える影響の考察不足
　5節 B. Accuracy 1段落目 "Regarding the clustering methods, no clustering or DBSCAN achieved higher accuracy than K-means."
　クラスタリングなしとDBSCANを使った場合に精度が上がり、k-meansを使った場合に精度が下がったことのみが記述されている。
　クラスタリング手法の妥当性が示せていない。

[修正案]
C.1-3同様の修正

C.2-6
3. Manual selection of regions to trim point clouds introduces uncontrolled subjectivity and possible bias. The lack of standardized, automated segmentation means results may vary depending on the operator’s choices. This undermines both reproducibility and scientific rigor. The authors fail to validate whether this human-driven preprocessing affects performance metrics. Automated, algorithmic region selection should be considered for future work.​
[原因]
・手動決定の明示
　3節 B. Methodology 2段落目 “Here, the coordinates of the vertices of a region where a person is located are determined manually, ”
　手動によって頂点を決めたことが明示されている。
・決定アルゴリズムの未記述
　5節 D. Processing of proposed system 2段落目 “We determined two vertices of the region where a person is located and then trimmed the point clouds.”
　二つの頂点の決定のために使用したアルゴリズムの記述がないため、作業者の手動によるものと判断されている。
・具体的な手順の欠如
　上記の手動による作業の詳細（具体的なパラメータなど）の記述がなく、研究の再現性が欠如している。
・モデル精度への影響についての記述不足
　手動に依存するノイズ除去がモデルの精度にどれほど影響を与えるかの記述がない。

[修正案]
3節「Proposed system」subsection「Methodology」2段落目“Here, the coordinates of the vertices of a region where a person is located are determined manually, ”
手動操作が客観指標（ボクセルごとの点の数など）に基づいている場合：
　客観指標を用いていることと、その指標の詳細を、上記の記述の直後に明記する。
手動操作が目視の場合：
　客観指標に基づく処理で再度結果を算出する。

C.2-7
4. Accuracy is used almost exclusively to evaluate the deep learning classifier, yet it is insufficient for multi-class tasks. The paper ignores essential metrics such as precision, recall, and F1-score, which would reveal more about model strengths and weaknesses. Reporting only overall accuracy risks obscuring important class-level deficiencies. The results section should present confusion matrices and more granular analysis. Inclusion of complementary metrics would provide much richer validation.​
[原因]
・結果が「Accuracy」に偏っている
　5節 B. Accuracy 1段落目
　Accuracyのみだと、クラス数に偏りがあった場合に、少数派のクラスを判別できているかが不明。Precision, Recall, F1-scoreの併記が必要。
　混同行列も示しているが、高精度の結果と低精度の結果しか混同行列は示されていない。
・多クラス分類においては指標の定義が不十分
　4節 D. Evaluation metric 2段落目
　TM, TP, TS, TT と FM, FP, FS, FT (mouse, pad, sit, typing)  という独自の変数名を使用しているが、何を何と間違えたかの情報が失われており、Accuracyの定義として不十分（例: FMがmouseをpadと間違えたのか、sitと間違えたのか曖昧）。

[修正案]
5節「Evaluation」
Table.2の結果にPrecision, recall, f1-scoreを併記する。

4節「Experiment setup」subsection「Evaluation metric」
2段落目のAccuracyの定義を以下のように修正する。
多クラス混同行列 (C)（真のクラス (i)、予測クラス (j) の件数 (C_{ij})）を定義。意味は「対角（正解）÷総数」
\mathrm{Accuracy}=\frac{\sum_{k=1}^{K} C_{kk}}{\sum_{i=1}^{K}\sum_{j=1}^{K} C_{ij}}

C.2-8
5. Despite apparent recurring misclassification, such as confusion between typing and pad operation, the paper does not analyze the causes. Persistent errors suggest underlying flaws in feature extraction or data representation. The discussion lacks proposals for remedying these weaknesses, such as refining features or adjusting sensor placement. Failure to explore and address error sources impedes overall model improvement. Readers are left without guidance for resolving similar misclassifications.​
[原因]
・誤分類の議論不足
　5節 B. Accuracy 1段落目 “no clustering or DBSCAN achieved higher accuracy than K-means. In terms of features, normals yielded higher accuracy when no clustering or DBSCAN was employed. ”
　k-meansを使うと精度が下がることを述べているが、その理由が考察されていない。
　
　5節 C. Confusion matrices 1段落目 “ However, there were frequent misclassifications of typing as pad operation. This is likely due to the difficulty in distinguishing whether both hands were touching the pad or the keyboard.”
　「両手がパッドかキーボードに触れているかの区別が難しいため」と記述されている。
　PointNet++という「点群の形状」を学習するモデルを使っている以上、「形状としてどう似ているのか」を論じるべき。データ表現の限界に触れる必要がある。

　必要な議論:
　モデルに入力している特徴が適切であるか。法線ベクトルなどで形状の違いを判断できるのか。
　センサの配置が適切であるか。真横に設置するのが適切なのか。

・Conclusionsの記述とデータの矛盾
　実際のデータにおいて、k-meansは多くの条件で分類精度を下げている。一方でConclusionsにおいて、k-meansは一貫して優れていると述べている。この矛盾が査読者の混乱を招いている。

実際のデータの傾向:
・Normals: (e) DBSCAN (0.69~0.99) > (a) No clustering (0.61~0.98) > (i) k-means (0.40~0.88)
・Dimensionality: (b) No clustering (最高0.94) > (j) k-means (最高0.92) > (f) DBSCAN
・FPFH: (d) No clustering / (e) DBSCAN の方が (l) k-means より高い傾向。

Conclusionsの記述:
"Among clustering techniques, K-means consistently outperformed no clustering and DBSCAN in terms of accuracy."

[修正案]
C.1-3同様

6節「Conclusions」3段落目 "Among clustering techniques, K-means consistently outperformed no clustering and DBSCAN in terms of accuracy."
クラスタリングに関する記述を実データTable 2～4と矛盾しないように修正する。k-meansが一様に高い傾向とは述べない。

C.2-9
6. The calculation of baseline accuracy is misleading and lacks grounding in the actual class distribution present in the dataset. The assumption of uniformity (i.e., 25% for each posture) may not reflect reality, thus skewing interpretation of performance. If class imbalance exists, reported accuracies may be inflated. The baseline should be empirically justified and adjusted according to true class proportions. Clarifying this would prevent misrepresentation of findings.​
[原因]
5節 B. Accuracy 1段落目 “Since we are classifying 4 posture classes, a baseline accuracy of 25% or higher is expected.”
4クラスの分類のためベースラインを25%としているが、これは4クラスの分布が均一であることを前提としている。

4節 B. Data acquisition
【学習データ (Training Data)】
・Mouse: 30秒 × 20回 = 600秒分
・Pad: 30秒 × 20回 = 600秒分
・Typing: 30秒 × 20回 = 600秒分
・Sitting still: 10秒 × 10回 = 100秒分

【テストデータ (Test Data)】
・Mouse: 30秒 × 1回 = 30秒分
・Pad: 30秒 × 1回 = 30秒分
・Typing: 30秒 × 1回 = 30秒分
・Sitting still: 10秒 × 1回 = 10秒分

クラス比率は3:3:3:1となっており、均一ではない。

[原因（指摘）]
＝＞データの時間長だけでなく、フレーム数も要確認
Table 1よりフレームレートは10fps。フレームレートが同じため、クラス比率も同じ。

[修正案]
5節「Evaluation」subsection「Accuracy」
"Since we are classifying 4 posture classes, a baseline accuracy of 25% or higher is expected. "
4クラス均一（25%）前提のベースラインをやめ、実クラス比率（時間長・フレーム数）に基づくベースラインを定義することを記載する。

6節「Conclusions」3段落目 
"Classification of four posture classes using subjects A to I as a test set yielded accuracy significantly above the 25% baseline ..."
Conclusionsにおける解釈もクラス比率に基づいたものに修正する。

C.2-10
7. LiDAR deployment in the study is limited to two sensors in a static environment, which is not representative of varied real-world office conditions. The lack of experiments in diverse, dynamic office environments restricts external validity. No attempts were made to test robustness across sensor configurations or locations. Expansion to multi-room or open-plan settings would yield more convincing results. Without this, claims of generalizability remain unsupported.​
[原因]
・条件を限定した理由の欠如
　4節 B. LiDAR deployment 1段落目 “The two LiDAR sensors were placed on a table facing each other. They were positioned 1.0 m away from the subject in a lateral direction and tilted down by 10◦ to make the PC easier to detect.  The PC was placed on the table in front of the subject. Fig. 6 shows the experiment site. “
　実際のオフィス環境とは異なる特定の環境に限定した理由が示されていない。理想化のために条件を絞っているのであれば、それを記述する必要がある。

条件が固定化されている要素：
・センサー配置の固定化と柔軟性の欠如
　LiDARの配置を2台、角度や距離も固定している。
・「静的な環境」という不自然さ
　実際のオフィスにおいては、歩き回る人や、ドアの開閉などの遮蔽物を想定する必要がある。
・部屋の規模と複雑さの不足
　複数の部屋、大部屋での検証がない。


・ 主張とエビデンスの不一致
　1節 3段落目 “ we propose an edge computing system that classifies the postures of people with hand movement in an office by using a LiDAR sensor network.”
　研究のスコープが広すぎる。「オフィスにおける行動認識システム」を提案しているが、実際に実験を行った条件は限定的になっている。限定的条件によって得られた結果から、「オフィス全般に適用できる仕組み」という一般化はできない。

・研究の限界の欠如
　6節
　上記の本研究における限界をConclusionsで示していない．

[修正案]
4節「Experiment setup」subsection「LiDAR deployment」
2台・固定配置・静的環境に限定した理由を述べる。
・目的
　「LiDARでタイピング等の手操作の種類を分類できること」自体が未確立
・静的環境の理由
　(i) 手以外の移動が支配的
　(ii) オクルージョン増
　(iii) 背景変動増
　(iv) ID追跡や分離が必須
　分類性能の良し悪しが動的要因に埋もれてしまうため、原因分解ができない。
＝＞まずは静的環境での実現

1節「Introduction」3段落目　
研究の位置づけを「実環境への最終適用」ではなく、「LiDAR点群からタイピング等の手操作の種類を分類可能であることを示すベースラインの確立）であることを明示する。
現時点の評価は統制された静的環境であり、動的遷移・複数人・遮蔽物・multi-room / open-plan 等の実環境条件への拡張はFuture worksで段階的に扱う旨を追記し、「オフィス一般」と読める一般化を避ける表現に直す。

6節「Conclusions」末尾
Future worksとして、本研究のスコープ外である以下の課題に段階的に取り組むことを明示する（multi-room / open-plan を含む実環境条件への拡張）。
・動的姿勢（静止姿勢だけでなく動きのある状態の認識）
・遷移（typing↔pad等の状態切替の過程／dynamic transitions）
・複数人（視野の重なり・相互遮蔽を含む）
・可変配置（センサ台数・配置の最適化、設置条件の変動）
・遮蔽物（家具・パーティション・ドア等による恒常的/一時的オクルージョンへの頑健化）
・複数部屋/オープンプラン（部屋構造・空間スケール・レイアウト差を含む環境での検証）

C.2-11
8. The use of PointCutmix for data augmentation is described, but the paper provides no comparative results to prove its effectiveness. There is no empirical evidence that augmentation substantially improves classification performance or model robustness. The absence of statistical comparison with non-augmented datasets diminishes confidence. Augmentation techniques should be validated and analyzed, showing before/after effects on model metrics. This gap undermines the contribution of the augmentation strategy.​
[原因]
Data augmentationのために行ったPointCutMixが結果にどう寄与したのか定量的に示されていない。Data augmentationがない場合は、被験者数が少ないため、過学習してしまうことを示す必要がある。

4節 D. Processing of proposed system 6段落目～8段落目
以下の単一のフローで記述されており、提示されているすべての結果はPointCutMixを通した後の数値だと解釈できる。比較の記述はない。
1.正規化（Normalization）を行う。
2.そのデータに対して データ拡張（PointCutMix）を実行する。
3.拡張された後のデータ（the remaining data）を 4:1 に分割して学習と検証に使う。

[修正案]
4節「Experiment setup」subsection「Processing of proposed system」7段落目
PointCutMix ありとなし、それぞれの条件で学習・検証を行うことを明示する。

5節「Evaluation」全体
PointCutMixなしの場合の結果を追加取得する。
PointCutMixありと、なし、それぞれの結果と有意差を示す。

C. 2-12
9. The literature review omits prominent technologies and recent studies using radar, higher-resolution sensors, or multi-modal fusion for posture classification. This leaves the paper lacking in contextual depth and critical comparison. Without considering state-of-the-art alternatives, the authors cannot convincingly argue for LiDAR as the optimal solution. A thorough, comparative review of sensor modalities would add scientific rigor. The current survey is not sufficient to justify system choices.​
[原因]
1節 1段落目:
"...utilizes sensory data ... and implements fuzzy finite state machines to model the behavior of the office workers [7]." 
"...biometric data and workplace environmental data through micro-surveys on mobile and web applications [8]."
最新のAI技術やセンサー技術ではなく、アンケートや古いアルゴリズム（Fuzzy FSM）と本研究を比較している。

1節 2段落目:
"Katayama et al. reported that point clouds can be utilized to classify human posture and presented a system for posture recognition and tracking [9]"
 "Glandon et al. reported that point clouds can be utilized for human identification and presented a system for posture estimation using data captured from walking people [10]"
比較対象が「単一の被験者」や「歩行シルエット」といった、限定的なLiDAR研究のみに絞られている。RadarやMulti-modalといった他のモダリティ（センサー種類）との比較を行っておらず、LiDARを選ぶ科学的根拠が不十分。

2節:
Related Works の構成が点群の処理方法（アルゴリズム）に偏っており、センサーの種類に関する議論が行われていない。

Related worksの構成
A. MODEL ARCHITECTURE
　点群をニューラルネットワークで処理するための手法
B. IMPROVEMENT FOR OBJECT DETECTION
　モデルにデータを読み込ませる前に行う特徴抽出のための手法

[修正案]
1節「Intoduction」1段落、2段落
・最新研究（AI・センサ技術・他モダリティ）の追加引用
・LiDARを採用する根拠づけ
・他モダリティとの位置づけ

2節「Related works」新設subsection
・既存研究（センサ技術・他モダリティ）の整理
・関連研究で挙げた研究に対する本研究の位置づけを明記

C. 2-13
10. References to broader concerns such as privacy, scalability, and actual workplace integration are absent from the discussion. For office monitoring applications, these aspects are critically important but were not addressed. This limits the scope of the paper and its potential impact on industry practice or policy. Addressing these larger issues would substantially increase its relevance. The omission weakens the overall contribution to the field.​
[原因]
・研究の位置づけが不明確
　1節 3段落目 “In light of this background, we propose an edge computing system that classifies the postures of people with hand movement in an office…”
研究の限界や位置づけの議論がない。オフィスへの実装を想定したシステムなのか、もっと前段階の基礎研究なのか不明確。

・動機の記述が「効率」のみ
　1節 1段落目 “The office-efficiency monitoring has been attracting people [1]–[6]. A recent report indicates that the main functions of office-efficiency monitoring include productivity monitoring, project tracking, and employee monitoring [1].”
　 モニタリングの目的が「生産性向上」や「従業員監視」という経営側の視点のみ。プライバシーへの言及がない

・拡張性の不明確さ
　3節
　研究の内容は一人の姿勢を二台のLiDARで見る。実際のオフィスであれば、数百人に拡張する必要があるが、その視点の記述がない
・比較対象が「アルゴリズム」のみ
　2節 A. System model 
　先行研究の分類が「モデルの構造」と「特徴抽出」という、数学・情報工学的な分類のみになっている。「オフィスモニタリングにおけるプライバシー保護の先行事例」や、「職場環境におけるセンサー設置の人間工学的な研究」などが欠如。

・結果の解釈の欠如
　5節
　得られた結果を踏まえて、実際のオフィス環境に適用可能かという議論が不足している。

[修正案]
C.1-4同様
1節「Introduction」末尾
本研究の既存研究との差分・位置づけを末尾に表記する。

6節「Conclusion」末尾
C.2-10同様。Future worksを記載する。

C.2-14
11. The manuscript repeatedly claims “nearly 100%” accuracy but does not present comprehensive raw data to back these assertions. Details in confusion matrices show substantial misclassification rates for some classes. Without full tables and error breakdowns, high-level claims risk misleading readers and stakeholders. Accurate, transparent reporting is essential to avoid overstating success. More detailed and honest result presentation is required for credibility.​
[原因]
・「Validation Accuracy（検証精度）」と「Test Accuracy（分類精度）」の混同
　6節 3段落 "We compared accuracies in each epoch of vadidation using each of classification models. The accuracy of all models was generally high."
　すべてのモデルで精度が概ね高かったと述べているが、これはFig. 8のValidation Accuracyのみを指している。分類精度も含めた、全体の評価として精度が高かったように誤解する。

　6節 3段落 "Classification of four posture classes using subjects A to I as a test set yielded accuracy significantly above the 25% baseline..."
　上記で概ね高いという記述があったのにもかかわらず、ここで25%を超えた、と低いハードルを提示している。精度が高いのか低いのか分からなくなる。
　
　検証精度について述べているのか、分類精度について述べているのか不明瞭。

[修正案]
6節「Conclusion」3段落目
検証精度とテスト精度を用語・数値ともに切り分けて記載する。

C.2-15
12. The paper lacks any form of statistical testing, such as t-tests, ANOVA, or confidence intervals, to demonstrate the significance and reliability of performance differences. Statistical evaluation is a standard expectation for experimental validation in machine learning research. By omitting this, the reported results may not withstand robust scrutiny. Incorporation of statistical analysis would greatly strengthen the scientific soundness of the conclusions. The current absence constitutes a critical gap.​
[原因]
・生の分類精度のみの比較
　5節 B. Accuracy 1段落目 “In all cases from Tables 2(a) through 2(l), the accuracy significantly exceeded this baseline.”
統計テストを行っていないのにもかかわらず、significantlyという統計用語を使用している。

　5節 B. Accuracy 1段落目 “Regarding the clustering methods, no clustering or DBSCAN achieved higher accuracy than K-means. In terms of features, normals yielded higher accuracy when no clustering or DBSCAN was employed”
統計的裏付けがないのにも関わらず、条件間で差が認められたことを主張している。被験者間の平均に対して、統計的手法による比較が必要。

　6節 3段落目
　5節 B. Accuracy同様、統計的裏付けがないのにもかかわらず、条件間で差が認められたことを主張している。

[修正案]
5節「Evaluation」subsection「Accuracy」1段落目
表形式で統計的手法の結果を追加する。

6節「Conclusion」3段落目
5節「Evaluation」で示した統計的根拠に基づいた主張に修正する。

Additional Questions:
Please confirm that you have reviewed all relevant files, including supplementary files and any author response files, which can be found in the "View Author's Response" link above (author responses will only appear for resubmissions): Yes, all files have been reviewed

1) Does the paper contribute to the body of knowledge?: yes

2) Is the paper technically sound?: yes

3) Is the subject matter presented in a comprehensive manner?: yes

4) Are the references provided applicable and sufficient?: paper needs revision

5) Are there references that are not appropriate for the topic being discussed?: No

5a) If yes, then please indicate which references should be removed.:


Reviewer: 3

Comments:
Strengths:

Novel extension of LiDAR-based classification to detailed hand-movement recognition.

Excellent experimental rigor, including multiple preprocessing variants and rich quantitative results.

Thorough related work review that situates the study in current 3D computer vision literature.

Clear, reproducible system design applicable to real-world smart environments.

Suggestions for Minor Improvement:


C.3-1
Discuss potential scalability to dynamic or multi-person scenarios (e.g., overlapping LiDAR fields).
[原因]
・拡張性の不明確さ
　3節
　研究の内容は一人の姿勢を二台のLiDARで見る。実際のオフィスを想定すると、複数人に拡張する必要があるが、その議論がない。

[修正案]
C.2-10同様。Future worksを記載する。

C.3-2
Add quantitative data on runtime performance and latency to validate real-time feasibility.
[原因]
1節 3段落目 “we propose an edge computing system that classifies…”
エッジコンピューティングシステムを提案しているのにもかかわらず、リアルタイム性の議論がない。エッジコンピューティングの意義が示されていない。

[修正案]
5節「Evaluation」新設subsection
使用ハードウェア上の前処理時間、推論時間を表形式で示す。

6節「Conclusion」末尾
Future worksとして、実オフィス環境におけるリアルタイム要件を述べる。

C.3-3
Summarize key results graphically (e.g., bar chart comparing feature-clustering accuracy).
[原因]
5節 B. Accuracy 1段落目 C. Confusion matrices 1段落目
Table 2, 3において、100以上の数字を結果として示し、本文中で説明を行っている。結果の全体的な傾向がつかみにくく、どの条件が一番良かったのかが分からない。

[修正案]
C.1-3同様：5節「Evaluation」Tableの修正

5節「Evaluation」
Table2/3にまとめている結果を折れ線グラフで可視化し、各条件の結果を可視化する。

C.3-4
Slightly condense repetitive parts in the conclusion for better focus.
[原因]
・既出のプロセスの説明の繰り返し
　6節 2段落目において、前セクションで既出の説明が繰り返されている。

　6節 2段落目
　・手順の説明
　"Multiple LiDAR sensors were utilized to capture multiple patterns of human posture from multiple people, and preprocessing, including trimming, feature estimation, clustering, and normalization, was performed before classification.”
　・実験の説明
　“Deep learning was implemented to perform classification while varying the data type, LiDAR placement, features used, and clustering method. We created classification models from training for each of the conditions and evaluated their classification accuracy.”
　・定義の説明
　"We defined the evaluation metric as the ratio of correctly classified samples and presented confusion matrices of models to show the number of correct labels and the biases of the inferred labels."
　評価指標の定義や、混同行列の役割といった標準的な知識を結論で再度説明している。

[修正案]
6節「Conclusion」2段落目
手順の再説明・評価指標の教科書的定義を削除し、主要な知見・限界・Future worksを述べる。

C.3-5
Improve visual readability of figures (larger fonts and simplified confusion matrices).
[原因]
・Figure, Tableのcaption, subcaptionが小さい。

・4節 Table 1. Specification of experiment.
　Table内のフォントサイズが小さい。本文のフォントサイズ未満になっている。
・4節 Figure 8. Classification accuracies of validation.
　グラフの縦軸ラベル、横軸・縦軸ラベルが小さい。凡例のフォントサイズが小さい。
・5節 Table 3. Table 4.
　混同行列の各要素の値を示すフォントサイズが小さい。
　混同行列は被験者一人の結果につき、4x4の表に数値を羅列する形式になっている。被験者9人分の表を交互に見比べる必要があり、理解が難しいと判断されている。

[修正案]
4節「Experiment setup」Table 1.
フォントサイズを大きくする。
4節「Experiment setup」Figure 8.
横軸・縦軸ラベル、凡例のフォントサイズを大きくする。それに伴い、図自体のサイズも大きくする。

5節「Evaluation」Table 3. Table 4.
C.1-3の通り、Precision, RecallをAccuracyと同じ表で提示し、混同行列は削除する。

Additional Questions:
Please confirm that you have reviewed all relevant files, including supplementary files and any author response files, which can be found in the "View Author's Response" link above (author responses will only appear for resubmissions): Yes, all files have been reviewed

1) Does the paper contribute to the body of knowledge?: Yes.
This paper presents a novel LiDAR-based edge computing system for classifying human postures—including fine hand movements—in an office environment. The authors propose a multi-LiDAR sensor network with a data preprocessing pipeline (trimming, feature estimation, clustering, normalization) combined with deep learning classification using PointNet++.

Key contributions include:

Extending prior LiDAR posture recognition to handle fine-grained hand motion.

A multi-sensor fusion architecture enabling spatially complete posture reconstruction.

Comprehensive evaluation across multiple features (normals, dimensionality features, variance proportion, FPFH) and clustering strategies (DBSCAN, K-means).

2) Is the paper technically sound?: Yes, with minor limitations.

The methodology is well designed and experimentally validated on multi-subject datasets (9 participants, 4 posture categories).

Results consistently show above-baseline classification accuracy (>60-99%) across feature-clustering combinations, demonstrating robustness.

Confusion matrices are detailed and provide insight into feature sensitivity (e.g., hand-position confusion between typing vs. pad use).

The system design (sensor fusion, edge processing, GPU-based classification) is clearly explained and reproducible.

Minor weaknesses:

C.3-6
Limited subject diversity (9 participants) and constrained office setting reduce generalization potential.
[原因]
C.2-1同様
・被験者が少ない（９人）
　・訓練データの被験者数
　5節 C. Data acquisition 1) Training data acquisition 6段落目 “The three subjects in this study are denoted as subjects A, B and C,”
　・テストデータの被験者数
　5節 C. Data acquisition 2) Test data acquisition 6段落目 “The nine subjects in this study are denoted as subjects A to I.”

C.2-10同様
・条件を限定した理由の欠如
　4節 B. LiDAR deployment 1段落目 “The two LiDAR sensors were placed on a table facing each other. They were positioned 1.0 m away from the subject in a lateral direction and tilted down by 10◦ to make the PC easier to detect.  The PC was placed on the table in front of the subject. Fig. 6 shows the experiment site. “
　実際のオフィス環境とは異なる特定の環境に限定した理由が示されていない。理想化のために条件を絞っているのであれば、それを記述する必要がある。

条件が固定化されている要素：
・センサー配置の固定化と柔軟性の欠如
　LiDARの配置を2台、角度や距離も固定している。
・「静的な環境」という不自然さ
　実際のオフィスにおいては、歩き回る人や、ドアの開閉などの遮蔽物を想定する必要がある。
・部屋の規模と複雑さの不足
　複数の部屋、大部屋での検証がない。

[修正案]
C.2-1同様
C.2-10同様

C. 3-7
No runtime or latency benchmarks for real-time performance are presented.
[原因]
C.3-2同様

[修正案]
C.3-2同様

C.3-8
The experimental focus is static postures rather than dynamic transitions, which would be relevant for practical monitoring.
[原因]
C.2-10同様
・条件を限定した理由の欠如
　4節 B. LiDAR deployment 1段落目 “The two LiDAR sensors were placed on a table facing each other. They were positioned 1.0 m away from the subject in a lateral direction and tilted down by 10◦ to make the PC easier to detect.  The PC was placed on the table in front of the subject. Fig. 6 shows the experiment site. “
　実際のオフィス環境とは異なる特定の環境に限定した理由が示されていない。理想化のために条件を絞っているのであれば、それを記述する必要がある。

[修正案]
C.2-10同様

3) Is the subject matter presented in a comprehensive manner?: Yes.
The manuscript is well structured and clear.

Figures and tables (especially Figs. 4–8, Tables 2–4) effectively illustrate feature generation, system setup, and results.

Related work is thoroughly reviewed, situating the study among existing 3D point-cloud classification frameworks (PointNet, PointCNN, ShellNet, A-CNN).

The experiment setup section is detailed and transparent, supporting reproducibility.

Minor improvements could enhance readability:

C.3-9
Some figure labels (e.g., confusion matrices) are dense and could be visually simplified.
[原因]
C.3-5同様

[修正案]
C.3-5同様

C.3-10
The conclusion section repeats earlier discussions; conciseness would improve clarity.
[原因]
C.3-4同様

[修正案]
C.3-4同様

4) Are the references provided applicable and sufficient?: Yes.
The reference list (44 items) is extensive and relevant, covering both classical and recent works (2017–2025) in LiDAR sensing, 3D feature extraction, clustering, and neural network-based classification. All major frameworks (PointNet++, FPFH, DBSCAN, K-means) are properly cited.

5) Are there references that are not appropriate for the topic being discussed?: No

5a) If yes, then please indicate which references should be removed.:

If you have any questions, please contact article administrator: Mr. Dharmendra Sharma dharmendra.sharma@ieee.org

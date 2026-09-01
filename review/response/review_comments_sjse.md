Dear Wataru Sano,

Track: Regular-03. Computer Engineering, Computer Science and ICT
Paper ID: #23
Paper title: Classification of postures of people with hand movement working in office environment by LiDAR sensor network
Review result: CONDITIONAL ACCEPT

The above manuscript has been reviewed for publication in the SEATUC Journal of Science and Engineering. We are afraid to inform you that we cannot publish the manuscript in its present form. Our Panel of Reviewers, however, found the manuscript interesting and requested a few modifications to the original. We would like to encourage you to submit a revised version to EasyChair, reflecting the Reviewers' comments stated below in this message.

In order to receive a 2nd Review, the Author(s) must submit a revised manuscript no later than September 18th, 2026. If we receive a revision after this date, the manuscript will be considered to be a new submission for the next publication of the Journal. Notification of the results of the 2nd Review will be sent by the middle of October.

When revising your manuscript, please note the followings:
1.      Resubmission is allowed only once. Therefore, please revise your manuscript carefully. The decision for the second review will be either ACCEPT or REJECT.
2.      When revising the manuscript in accordance with the Reviewers' comments, please ensure that any discrepancies do not arise in the context due to the revisions.
3.      When the Authors make any additions or corrections, the section(s) should be MARKED so that the Reviewer can clearly see all the changes made.
4.      No change in the list of authors is as a rule permitted.　Nonetheless, if in revising a manuscript the need arises to modify the list of authors, a request can be submitted by attaching　a written explanation at the time of the revision. When requesting it, be sure to state that fact in the "Reply Letter"(referred in “5.(1)(b)"). Your request will be accepted if the Editorial Committee deems the reasons cited in the written explanation valid. 
5.      Authors are requested to upload the followings.
(1)     PDF files for second review 
 (a)    Revised Manuscript PDF file with marks for reviewer including all figures, tables, etc.
 (b)    Reviewers' comments and Reply Letter PDF file
(2)     Electronic source files for publishing (upper limit: 10MB per one file)
 (a)    Camera-ready Manuscript PDF file without marks including all figures, tables, etc.
 (b)    Source files (LaTeX or Word) of the Camera-ready Manuscript PDF (referred in “5.(2)(a)")
 (c)    Reference List Excel file (Download from: https://surl.jp/VpCnmhU8)
6.      If your manuscript was not prepared using the dedicated template, SJSE Secretariat will send you a request to rewrite your manuscript using the dedicated format.

Thank you for submitting the results of your research to our Journal. We look forward to receiving your revised manuscript.

Sincerely,
Nicodimus Retdian
Editor in Chief of the SEATUC Journal of Science and Engineering
Shibaura Institute of Technology

SUBMISSION: 23
TITLE: Classification of postures of people with hand movement working in office environment by LiDAR sensor network

----------------------- REVIEW 1 ---------------------

SUBMISSION: 23
TITLE: Classification of postures of people with hand movement working in office environment by LiDAR sensor network

----------- Overall evaluation -----------
SCORE: 4 (conditional accept)
----- TEXT:
This paper proposes a system that uses a LiDAR sensor network to classify the posture—including hand movements—of people working in an office. Although the reviewer recognizes this paper deals with a useful technology,it has some ambiguous descriptions and some key statements are missing. Please revise the manuscript in the following points.


C.1-1
1. This study uses LiDAR to investigate movements of human hands. Whilst the introduction mentions the need to measure movements of human hands, it does not refers to the advantages of using LiDAR. Please add descriptions to justify the use of LiDAR for this objective.
[原因]
1節「Introduction」は手元分類の必要性を述べ、提案で LiDAR sensor network を使うと宣言している。LiDAR を選ぶ利点（カメラとの差、照明、プライバシー、3次元形状の取得など）は書かれていない。

1節「Introduction」3段落目
"Hand-movement classification is necessary to record these desk-work activities."
手元分類の必要性

1節「Introduction」5段落目
"This paper proposes a system that classifies the postures of people with hand movement in an office by using a LiDAR sensor network."
LiDAR sensor networkを使うことの宣言

1節「Introduction」4段落目
"Their system acquired point cloud data with a small light detection-and-ranging (LiDAR) unit and classified posture using machine learning on data from a sitting person."
ここは先行研究の手法紹介であり、本研究が LiDAR を採用する根拠ではない。

C.1-2
2. The term ‘participants’ is used as subjests. Please revise to modify them to 'experiment participants’.
[原因]
実験協力者の呼称を論文中ではsubjectsとしている。一部participantsとなっており、統一もされていない。
査読者はexperiment participantsに統一するべきと判断した。

4節「Experiment setup」subsection「Data acquisition」subsubsection「Training data acquisition」4段落目
"The three subjects in this study are denoted as subjects A, B, and C."

4節「Experiment setup」subsection「Data acquisition」subsubsection「Test data acquisition」2段落目
"The 28 subjects in this study are denoted as subjects A to AB."

4節「Experiment setup」subsection「Experimental system」2段落目
"3 contributors provided training data."
"28 contributors provided test data."
表記ゆれ: contributors

1節「Introduction」4段落目
"The experiments included only one participant."
表記ゆれ: participant

C.1-3
3. In section 4.1, the terms ‘A’ and ‘AB’ are used to refer to test data; these represent data from the experimental participants respectively. Plase add descriptions on how the authors acquired these test data before referring to them.
[原因]
"A" / "AB" が、取得方法の説明より先に出ている。4.1 で装置と日付の説明に "test data A, B, and C" と "test data A to AB" を使い、誰のどのデータかは 4.3.2 まで書かれない。

4節「Experiment setup」subsection「Experimental system」1段落目
"An NVIDIA Jetson Xavier NX edge computer was used for training data and test data A, B, and C acquisition."
"An NVIDIA Jetson Orin nano edge computer was used for test data A to AB acquisition."
4節「Experiment setup」subsection「Experimental system」2段落目
"Training data and test data A, B, and C were acquired on 9 December 2022."
"Test data A to AB were acquired on 12 December 2024."
用語の初出位置。A, B, C...が被験者であることは明示されていない。単にデータの名称として扱われている。

取得の定義は後続の 4節「Experiment setup」subsection「Data acquisition」subsubsection「Test data acquisition」2段落目
"The 28 subjects in this study are denoted as subjects A to AB."
"Test data with subjects A to AB is called test data A to AB."
ここで被験者であることが明示される。

C.1-4
4. In Section 4.5 ‘Evaluation metric’, the classification models were trained using data obtained from three experimental participants; however, there are no descriptionis on how these three participants were selected. Please add details on the criteria of participants selection with the discussions on whether changing to other criteria would affect the results.
[原因]
データを取得した被験者の選定基準がない。基準を変えた場合に結果が変わるかの議論もない。

4節「Experiment setup」subsection「Evaluation metric」1段落目
"The classification models trained using the augmented data from three subjects were evaluated using the test data from twenty-eight subjects."
コメントで指摘されている箇所

4節「Experiment setup」subsection「Data acquisition」subsubsection「Training data acquisition」4段落目
"The three subjects in this study are denoted as subjects A, B, and C."
"Training data with subjects A, B, and C is called training data A, B, and C."
データ取得の箇所

4節「Experiment setup」subsection「Experimental system」2段落目
"3 contributors provided training data. 28 contributors provided test data."
training data, test dataの初出箇所

いずれも人数のみの記述となっていて、選定基準に関する記述はない。


C.1-5
5. The positions of Figure 5 (c) ‘Proportion of variances’ and (d) ‘FPFH’ are reversed. Please swap them.
[原因]
5節「Evaluation」subsection「Validation results」の Figure 5 の並びが (a),(b),(d),(c)となっている。
 が対象。査読者は (c) と (d) の位置が逆だと判断した。

5節「Evaluation」subsection「Validation results」Figure 5 キャプション
"(c) Proportion of variances"
"(d) FPFH"
"Classification accuracies of validation."

現行ソースでは (c) に Accuracies_of_validation_POV.png、(d) に Accuracies_of_validation_FPFH.png を割り当てている。本文の言及順も (c) POV → (d) FPFH。

5節「Evaluation」subsection「Validation results」2段落目
"For proportion of variance (Fig. 5(c)), validation accuracy remained high with a similar k-means decrease."
"For FPFH (Fig. 5(d)), validation accuracy remained high; DBSCAN showed larger epoch-to-epoch variation than the other clustering settings."

指摘は組版後 PDF での (c)/(d) の見え方、または投稿版での図の割り当てに対するもの。

C.1-6
In addtion, in discussions of these results, please clarify the level of accuracy that would be considered sufficient to indicate that the model has been sufficiently trained.
[原因]
十分学習できたと判断する精度の数値基準が、validation にも test にもない。training accuracy の報告もない。

5節「Evaluation」subsection「Validation results」2段落目
"For normals (Fig. 5(a)), validation accuracy remained high under all clustering settings."
"For dimensionality features (Fig. 5(b)), validation accuracy remained high; k-means showed a slight decrease relative to no clustering and DBSCAN."
"For proportion of variance (Fig. 5(c)), validation accuracy remained high with a similar k-means decrease."
"For FPFH (Fig. 5(d)), validation accuracy remained high; DBSCAN showed larger epoch-to-epoch variation than the other clustering settings."
"high" は定性であり、数値の合格線ではない。

5節「Evaluation」subsection「Validation results」3段落目
"Training terminated if validation accuracy did not improve within 15 epochs after the best epoch."
打ち切り条件は epoch 数であり、精度の下限ではない。

5節「Evaluation」subsection「Accuracy」1段落目
"Four posture classes yield a 25% baseline accuracy under uniform random guessing."
"Accuracy exceeded the 25% baseline in all cases in Table 2."
25% は機会水準であり、「十分学習できた」基準ではない。

6節「Conclusion」3段落目
"Validation accuracy reached nearly 100% for all feature and clustering combinations, with minor differences among clustering methods."
ほぼ 100% という事実の報告であり、「十分」の基準の定義ではない。

6節「Conclusion」4段落目
"Test accuracy remained below 1.0 for several test subjects and preprocessing combinations in Table 2."
上限未達の事実であり、十分性の定義ではない。

C.1-7
6. There are blank lines on the right-hand side of page 5. Please adjust the layout of the manuscript to remove them, such as moving 5.Conclusion to the page 5.
[原因]
5節「Evaluation」末尾
5節で参照した表の後に、6節「Conclusion」を置くようにしているため、5節の末尾に空白が生じている。査読者はこの空白が不適切であると判断した。

----------------------- REVIEW 2 ---------------------

SUBMISSION: 23
TITLE: Classification of postures of people with hand movement working in office environment by LiDAR sensor network

----------- Overall evaluation -----------
SCORE: 4 (conditional accept)
----- TEXT:
The paper addresses a meaningful problem: classifying fine-grained office desk-work states such as mouse operation, trackpad operation, typing, and sitting still using a LiDAR sensor network. The motivation is clearly stated. The paper also presents a real experimental system using multiple LiDAR sensors, point-cloud preprocessing, feature extraction, clustering, downsampling, normalization, and PointNet++ classification. The experiment includes training data from three subjects and test data from twenty-eight subjects, which gives some evidence of generalization beyond the training subject. The comparison of feature and clustering combination is useful (section 5.2 table 2).

However, there are some ambiguous desciprionts in the manuscript and also it lacks some key descprionts to show the benefits of the proposed method. Please revise the manuscript in the following points:


C.2-1
- Using accuracy alone as the evaluation metric is not sufficient. The four classes are fine-grained and likely to be confused with one another. For example, mouse vs pad operation. Pleased add a confusion matrix and results of class-wise precision, recall, F1 score for each preprocessing configuration.
[原因]
評価指標が Accuracy のみになっており、4クラス間の正誤の組み合わせが評価できないと査読者に判断された。

4節「Experiment setup」subsection「Evaluation metric」2段落目
"Accuracy was utilized to evaluate the classification models, defined as (TM+TP+TS+TT)/(TM+TP+TS+TT+FM+FP+FS+FT)"
"FM, FP, FS, and FT are the number of point clouds that were not correctly classified."
Accuracyの定義。どのクラスをどのクラスに間違えたかという情報が一つの数にまとまり、区別できなくなっている。

5節「Evaluation」subsection「Accuracy」1段落目
"Table 2 shows the accuracy for all twelve combinations of features and clustering methods used."
Table 2 の値は被験者ごとの Accuracy のみ。

C.2-2
- Section 4.4 states that: "data were split 4.1 for training and validation.
It should be correctly "4:1 training/validation split is performed randomly over frames, overload trials, and subjects." Please revise this expression to a correctv one.
[原因]
4.4 の分割記述が「4:1」だけで、分割の単位（frame / trial / subject）と無作為かどうかが書かれていない。査読者はこの表現を不正確と判断した。

4節「Experiment setup」subsection「Processing of proposed system」2段落目
"Data were split 4:1 for training and validation; multi-scale grouping (MSG) formed PointNet++ groups."

何を 4:1 に分けたか、同一被験者内か、frame 単位か、がこの文にない。査読者が求めた
"4:1 training/validation split is performed randomly over frames, overload trials, and subjects."
に相当する情報がない。

C.2-3
- Please explain whether validation data includes the same subjects as the training data.  Although the validation accuracy in Fig. 5 is nearly 100%, the test accuracy in table 2 is much lower and varies across subjects.
[原因]
validation が学習と同一の 3 被験者由来かが明示されていない。分割は学習用データに対する 4:1 であり、test は 28 名で精度が下がる。この差の説明がない。

4節「Experiment setup」subsection「Processing of proposed system」1段落目
"PointCutMix augmented normalized training data by replacing the top λ% of nearest-neighbor-matched points between three point clouds A, B, and C"

4節「Experiment setup」subsection「Processing of proposed system」2段落目
"Data were split 4:1 for training and validation;"
この直前までが A, B, C の学習データ処理なので、validation も同一 3 名からの分割と読める。同一被験者を含むかは書いていない。

5節「Evaluation」subsection「Validation results」1段落目
"Fig. 5 shows validation accuracy per epoch for each feature type; each subfigure plots three lines for no clustering, DBSCAN, and k-means."
validationの精度は各特徴でほぼ100%に近い。

C.2-4
- Although the current comparison shows which feature/clustering combination works better, it does not show whether the proposed feature extraction and clustering are necessary.
Please add at least one stronger baseline method, for example, pointnet++ using raw XYZ coordinates without additional features or PointNet/PointNet++ without clustering would be appropriate.
[原因]
比較は 4 特徴 × 3 クラスタリング（None / DBSCAN / k-means）の 12 条件で行っている。査読者の指摘する特徴抽出なしの raw XYZ、および PointNet（++ でない）の baseline がない。baselineがないため、特徴量、PointNet++の有効性が示せていないと判断された。
None はクラスタリングなしであり、追加特徴抽出なしではない。

5節「Evaluation」subsection「Accuracy」1段落目
"Table 2 shows the accuracy for all twelve combinations of features and clustering methods used."

3節「Proposed system」subsection「Methodology」3段落目
"Four types of features are extracted from the trimmed point clouds: normals, dimensionality features, proportion of variance, and FPFH."
raw XYZ のみの条件はない。

2節「Related works」subsection「Model architecture」5段落目
"PointNet++ is adopted in the proposed system because hierarchical grouping extracts local geometry from sparse desk-region point clouds without voxelization."
分類器は PointNet++ に固定。PointNet との比較はない。

Additional comments:

C.2-5
- the authors should be careful when writing the manuscript. For example, the author name is : "...Trovator" but the biography is "...Trovato". Which one is correct?
[原因]
論文冒頭　著者名・論文末尾 biography
査読者は著者名が"Trovator"となっており、biographyの"Trovato" が食い違っていると指摘。原稿上の著者名のスペルミス。

C.2-6
- some typos and english grammar existed in the manuscript.
[原因]
原稿全体に英語の誤り・不自然な表現が残っている。

論文冒頭
Trovator -> Trovato（C.2-5同様）

4.1 Expeirmental system
Expeirmental -> Experimental

論文末尾 biography 1番目（Wataru Sano）
"Graduate School of Electric Engineering and Computer Science"

論文末尾 biography 2番目（Jumpei Watanabe）
"Graduate School of Electrical Engineering and Computer Science"
Electric/Electrical
学部名の綴りが論文内で一致していない。

C.2-7
- check again the reference, in section 2.1, the authors stated "... presented PointNet [11]. But the reference [11] is not the PointNet paper.
[原因]
PointNet の初出引用が PointNet 論文ではない。[11]は多クラス分類の指標解説である。PointNet++の論文は[21]である。

2節「Related works」subsection「Model architecture」2段落目
"Qi et al. presented PointNet [11]."
著者名は正しいが、引用が誤り。

2節「Related works」subsection「Model architecture」5段落目
"PointNet++ is adopted in the proposed system because hierarchical grouping extracts local geometry from sparse desk-region point clouds without voxelization [21]."
ここでの引用は正しくPointNet++の論文を引用している。

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


C.1-1（原稿反映完了）
1. This study uses LiDAR to investigate movements of human hands. Whilst the introduction mentions the need to measure movements of human hands, it does not refers to the advantages of using LiDAR. Please add descriptions to justify the use of LiDAR for this objective.
[原因]
LiDARの技術的背景の記述が欠けている。背景もなく突然、先行研究でLiDARを用いていることが述べられ、査読者はLiDAR採用の妥当性が十分に示されていないと判断した。

1節「Introduction」3段落目末尾（手分類の必要性）、4段落目先頭の間にLiDARの技術的背景がない。

[修正案]
以下をLiDARの技術背景として追記する。
・死角をカバーできる
・点群の高密度を確保できる
・物体の全面を捉えられる

略語展開を追記段落へ移す。

1節「Introduction」3段落目末尾と4段落目先頭の間
新段落として追記:
"Light detection-and-ranging (LiDAR) acquires 3D data for recognizing indoor movements of people and objects \cite{9795869,oka2021spatial,10159661}."
"Multiple LiDAR sensors provide the following benefits \cite{oka2021spatial,10159661}."
  "The sensors cover indoor spaces without blind spots."
  "Integration of multi-view point-cloud data increases point density."
  "Multi-view integration captures the full surface of a person."

1節「Introduction」4段落目
修正前:
"Their system acquired point cloud data with a small light detection-and-ranging (LiDAR) unit and classified posture using machine learning on data from a sitting person \cite{9767292}."
修正後:
"Their system acquired point cloud data with a small LiDAR unit and classified posture using machine learning on data from a sitting person \cite{9767292}."

R.1-1
We have added the technical background of LiDAR and the advantages of multiple LiDAR sensors. We have modified the expansion of the LiDAR abbreviation.
We have added the fourth paragraph in Section 1. We have modified the fifth paragraph in Section 1.
We made this modification because the justification for using LiDAR was insufficient.

(Fourth paragraph, Section 1)
Light detection-and-ranging (LiDAR) acquires 3D data for recognizing indoor movements of people and objects [9], [10], [11].
Multiple LiDAR sensors provide the following benefits [10], [11].
The sensors cover indoor spaces without blind spots.
Integration of multi-view point-cloud data increases point density.
Multi-view integration captures the full surface of a person.
[9] Z. Sun, Q. Ke, H. Rahmani, M. Bennamoun, G. Wang, and J. Liu, ‘‘Human action recognition from various data modalities: A review,’’ IEEE Transactions on Pattern Analysis and Machine Intelligence, pp. 1–20, 2022.
[10] M. Oka, R. Shinkuma, T. Sato, E. Oki, T. Iwai, K. Nihei, E. Takahashi, D. Kanetomo, and K. Satoda, ‘‘Spatial feature-based prioritization for transmission of point cloud data in 3D-image sensor networks,’’ IEEE Sensors Journal, vol. 21, no. 20, pp. 23145–23161, 2021.
[11] K. Akiyama, K. Azuma, R. Shinkuma, and J. Shiomi, ‘‘Real-Time Adaptive Data Transmission Against Various Traffic Load in Multi-LIDAR Sensor Network for Indoor Monitoring,’’ IEEE Sensors Journal, vol. 23, no. 15, pp. 17676–17689, 2023.


C.1-2（原稿反映完了）
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

[修正案]
実験協力者の呼称を experiment participants に統一する。
・subjects を experiment participants に置換する
・contributors を experiment participants に置換する
・participant を experiment participant に置換する

4節「Experiment setup」subsection「Data acquisition」subsubsection「Training data acquisition」4段落目
修正前:
"The three subjects in this study are denoted as subjects A, B, and C."
"Training data with subjects A, B, and C is called training data A, B, and C."
修正後:
"The three experiment participants in this study are denoted as experiment participants A, B, and C."
"Training data with experiment participants A, B, and C is called training data A, B, and C."

4節「Experiment setup」subsection「Data acquisition」subsubsection「Test data acquisition」2段落目
修正前:
"The 28 subjects in this study are denoted as subjects A to AB."
"Test data with subjects A to AB is called test data A to AB."
修正後:
"The 28 experiment participants in this study are denoted as experiment participants A to AB."
"Test data with experiment participants A to AB is called test data A to AB."

4節「Experiment setup」subsection「Experimental system」2段落目
修正前:
"3 contributors provided training data."
"28 contributors provided test data."
修正後:
"3 experiment participants provided training data."
"28 experiment participants provided test data."

1節「Introduction」4段落目
修正前:
"The experiments included only one participant."
修正後:
"The experiments included only one experiment participant."

R.1-2
We have modified the terms subjects, participants, and contributors to experiment participants.
We have modified the fifth paragraph in Section 1, the fourth paragraph in Section 4.3.1, and the second paragraph in Section 4.3.2.
We made this modification because the terminology referring to experiment participants was not unified.

(Fifth paragraph, Section 1)
The experiments included only one experiment participant.

(Fourth paragraph, Section 4.3.1)
The three experiment participants in this study are denoted as experiment participants A, B, and C.
Training data with experiment participants A, B, and C is called training data A, B, and C.

(Second paragraph, Section 4.3.2)
The 28 experiment participants in this study are denoted as experiment participants A to AB.
Test data with experiment participants A to AB is called test data A to AB.

C.1-3（原稿反映完了）
3. In section 4.1, the terms ‘A’ and ‘AB’ are used to refer to test data; these represent data from the experimental participants respectively. Plase add descriptions on how the authors acquired these test data before referring to them.
[原因]
記号A-ABは被験者ラベルだが、その定義を行う前にデータセットのラベルとして参照している。査読者は初出時にデータセットのラベルとして扱われた記号が、いつの間にか被験者のラベルとしてつかわれていることを指摘している。

4節「Experiment setup」subsection「Experimental system」1段落目
"An NVIDIA Jetson Xavier NX edge computer was used for training data and test data A, B, and C acquisition."
"An NVIDIA Jetson Orin nano edge computer was used for test data A to AB acquisition."
記号A-ABの初出。この位置にデータセットラベルとして、記号A-ABを使うのは誤り。

4節「Experiment setup」subsection「Data acquisition」subsubsection「Test data acquisition」2段落目
"The 28 subjects in this study are denoted as subjects A to AB."
"Test data with subjects A to AB is called test data A to AB."
ここで初めて被験者ラベルとして記号A-ABを使うべき。

[修正案]
4.1では記号A-ABをデータセットラベルとして使わない。人数も識別子にしない。
・装置の説明では日付で区別する
・日付の説明では取得対象（training / test）と日付で区別する

被験者数と被験者ラベルの初出は4.3に残す。呼称はC.1-2に従う。

4節「Experiment setup」subsection「Experimental system」1段落目
修正前:
"An NVIDIA Jetson Xavier NX edge computer was used for training data and test data A, B, and C acquisition."
"An NVIDIA Jetson Orin nano edge computer was used for test data A to AB acquisition."
修正後:
"An NVIDIA Jetson Xavier NX edge computer was used for training data and test data acquisition on 9 December 2022."
"An NVIDIA Jetson Orin nano edge computer was used for test data acquisition on 12 December 2024."

4節「Experiment setup」subsection「Experimental system」2段落目
修正前:
"Training data and test data A, B, and C were acquired on 9 December 2022."
"Test data A to AB were acquired on 12 December 2024."
修正後:
"Training data and test data were acquired on 9 December 2022."
"Test data were acquired on 12 December 2024."

4節「Experiment setup」subsection「Experimental system」2段落目
修正前:
"3 contributors provided training data."
"28 contributors provided test data."
修正後:
削除する。人数は4.3のラベル定義に残す。

R.1-3
We have modified the descriptions of training data and test data in to distinguish the data by acquisition dates. We have deleted the labels A to AB from the descriptions of the data.
We have modified the first paragraph and the second paragraph in Section 4.1.
We made this modification because it was ambiguous whether the labels A to AB referred to datasets or to experiment participants.

(First paragraph, Section 4.1)
An NVIDIA Jetson Xavier NX edge computer was used for training data and test data acquisition on 9 December 2022.
An NVIDIA Jetson Orin nano edge computer was used for test data acquisition on 12 December 2024.

(Second paragraph, Section 4.1)
Training data and test data were acquired on 9 December 2022.
Test data were acquired on 12 December 2024.

C.1-4（原稿反映完了）
4. In Section 4.5 ‘Evaluation metric’, the classification models were trained using data obtained from three experimental participants; however, there are no descriptionis on how these three participants were selected. Please add details on the criteria of participants selection with the discussions on whether changing to other criteria would affect the results.
[原因]
テストデータ28名に対して、学習データ3名は人数が少なく、選定基準の影響があると査読者は判断した。そのため、査読者は学習データ3名の選定基準を求めている。

4節「Experiment setup」subsection「Experimental system」2段落目
"3 contributors provided training data."
3人の被験者の初出。ここに選定基準の記述がない。

[修正案]
協力者31名の選定基準を明示する。
・年齢帯は20代
・日常的にPCを使うこと
学習データ3名は31名から無作為抽出とする。
呼称はC.1-2に従う。

4節「Experiment setup」subsection「Data acquisition」subsubsection「Training data acquisition」1段落目の前
新段落として追記:
"We selected 31 experiment participants."
  "The 31 experiment participants were in their 20s."
  "The 31 experiment participants used a PC daily."

4節「Experiment setup」subsection「Data acquisition」subsubsection「Training data acquisition」4段落目
修正前:
"The three subjects in this study are denoted as subjects A, B, and C."
"Training data with subjects A, B, and C is called training data A, B, and C."
修正後:
"We randomly sampled three experiment participants from the 31 experiment participants."
"The three experiment participants in this study are denoted as experiment participants A, B, and C."
"Training data with experiment participants A, B, and C is called training data A, B, and C."

4節「Experiment setup」subsection「Data acquisition」subsubsection「Test data acquisition」2段落目
修正前:
"The 28 experiment participants in this study are denoted as experiment participants A to AB."
"Test data with experiment participants A to AB is called test data A to AB."
修正後:
"We used 28 experiment participants from the 31 experiment participants."
  "The 28 experiment participants were not sampled for training."
"The 28 experiment participants in this study are denoted as experiment participants A to AB."
"Test data with experiment participants A to AB is called test data A to AB."

R.1-4
We have added the selection criteria for the 31 experiment participants. We have added that three experiment participants for training were randomly sampled from the 31 experiment participants. We have added that the 28 experiment participants for testing were not sampled for training.
We have added the first paragraph in Section 4.3.1. We have modified the fifth paragraph in Section 4.3.1. We have modified the second paragraph in Section 4.3.2.
We made this modification because the selection criteria were unclear. The impact of the selection criteria on the results was difficult to judge.

(First paragraph, Section 4.3.1)
We selected 31 experiment participants.
The 31 experiment participants were in their 20s.
The 31 experiment participants used a PC daily.

(Fifth paragraph, Section 4.3.1)
We randomly sampled three experiment participants from the 31 experiment participants.

(Second paragraph, Section 4.3.2)
We used 28 experiment participants from the 31 experiment participants.
The 28 experiment participants were not sampled for training.

C.1-5（原稿反映完了）
5. The positions of Figure 5 (c) ‘Proportion of variances’ and (d) ‘FPFH’ are reversed. Please swap them.
[原因]
5節「Evaluation」subsection「Validation results」右ページの Figure 5 の並びが 上から(a),(b),(d),(c)となっている。図とラベルは対応しているが、順番通りになっていない。
査読者はラベルを順番通りにするように指摘している。

[修正案]
5節「Evaluation」subsection「Validation results」Figure 5
Figure 5 の下段で (c) と (d) の位置を入れ替える。
・図とキャプションの対応は変えない
・本文の Fig. 5(c) / Fig. 5(d) の参照は変えない

R.1-5
We have modified the positions of Figure 5 (c) and (d).
We have modified Figure 5 in Section 5.1.
We made this modification because the positions of Figure 5 (c) and (d) were reversed.

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

[修正案]
3クラスの結果（pad/typingは似ているため区別せず、3クラスで分類を実施）
3クラスの結果を網羅的かつ簡潔に本文に追記する。（表の追加は不要）。

5節「Evaluation」subsection「Accuracy」（表の直後に新段落）
"We treated pad operation and typing as one posture class."
  "Pad operation and typing are similar in hand placements near the keyboard and trackpad."
"We evaluated three posture classes: mouse operation, pad-or-typing, and sitting still."
"The mean three-class accuracy reached 0.90."
  "Normals with DBSCAN reached a mean three-class accuracy of 0.94."
"The results indicate that separation of pad operation and typing was difficult in four-class classification."

6節「Conclusion」（4段落目末尾に追記）
"The mean three-class accuracy reached 0.90."
"The results indicate that separation of pad operation and typing was difficult in four-class classification."

R.1-6
We have added three-class classification results that treat pad operation and typing as one posture class. We have added the mean three-class accuracy and the mean three-class accuracy.
We have added a paragraph after Table 2 in Section 5.2. We have modified the fourth paragraph in Section 6.
We made this modification because we could not clearly show that sufficient model training had been achieved.

(Paragraph after Table 2, Section 5.2)
We treated pad operation and typing as one posture class.
Pad operation and typing are similar in hand placements near the keyboard and trackpad.
We evaluated three posture classes: mouse operation, pad-or-typing, and sitting still.
The mean three-class accuracy reached 0.90.
Normals with DBSCAN reached a mean three-class accuracy of 0.94.
The results indicate that separation of pad operation and typing was difficult in four-class classification.

(Fourth paragraph, Section 6)
The mean three-class accuracy reached 0.90.
The results indicate that separation of pad operation and typing was difficult in four-class classification.

C.1-7（原稿反映完了）
6. There are blank lines on the right-hand side of page 5. Please adjust the layout of the manuscript to remove them, such as moving 5.Conclusion to the page 5.
[原因]
5節「Evaluation」末尾
5節で参照した表の後に、6節「Conclusion」を置くようにしているため、5節の末尾に空白が生じている。査読者はこの空白が不適切であると判断した。

[修正案]
6節「Conclusion」を5節本文の直後から開始し、5ページ右段の空白を埋める。

R.1-7
We have modified the starting position of Section 6.
We have modified the layout on page 5.
We made this modification because blank lines remained on the right-hand side of page.

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

[修正案]
混同行列を回答レターに貼り付ける。本文に重要結果のみTP, TN, FP, FNを載せ
る（査読者の指摘ポイント、読者にとって考察の必要と思われる箇所）
3クラス分類・4クラス分類両方とも含める。

5節「Evaluation」subsection「Accuracy」（C.1-6 の3クラス段落の直後）
"We report four-class and three-class confusion counts on test data A."
"For normals without clustering, pad operation yielded 172 false predictions as mouse operation."
  "Typing yielded 103 false predictions as pad operation."
"For normals with DBSCAN, pad operation yielded 30 false predictions as mouse operation."
  "Typing yielded 230 false predictions as pad operation."
"For normals without clustering, pad-or-typing yielded 189 false predictions as mouse operation."
"For normals with DBSCAN, pad-or-typing yielded 30 false predictions as mouse operation."
"Full four-class and three-class confusion matrices for all twelve preprocessing configurations appear in the response letter."

6節「Conclusion」（4段落目、R.1-6追記の直前に1文）
"Four-class confusion counts showed frequent false predictions of typing as pad operation."

R.2-1
We have added four-class and three-class confusion counts. We have added four-class and three-class confusion matrices for all twelve preprocessing configurations to this reply letter.
We have added a paragraph after Table 2 in Section 5.2. We have modified the fourth paragraph in Section 6.
We made this modification because accuracy alone did not show which posture classes were confused with one another.

(Paragraph after Table 2, Section 5.2)
We report four-class and three-class confusion counts on test data A.
For normals without clustering, pad operation yielded 172 false predictions as mouse operation.
Typing yielded 103 false predictions as pad operation.
For normals with DBSCAN, pad operation yielded 30 false predictions as mouse operation.
Typing yielded 230 false predictions as pad operation.
For normals without clustering, pad-or-typing yielded 189 false predictions as mouse operation.
For normals with DBSCAN, pad-or-typing yielded 30 false predictions as mouse operation.
Full four-class and three-class confusion matrices for all twelve preprocessing configurations appear in the response letter.

(Fourth paragraph, Section 6)
Four-class confusion counts showed frequent false predictions of typing as pad operation.

C.2-2（原稿反映完了）
- Section 4.4 states that: "data were split 4.1 for training and validation.
It should be correctly "4:1 training/validation split is performed randomly over frames, overload trials, and subjects." Please revise this expression to a correctv one.
[原因]
4.4 の分割記述が「4:1」だけで、分割の単位（frame / trial / subject）と無作為かどうかが書かれていない。査読者はこの表現を不正確と判断した。

4節「Experiment setup」subsection「Processing of proposed system」2段落目
"Data were split 4:1 for training and validation; multi-scale grouping (MSG) formed PointNet++ groups."

何を 4:1 に分けたか、同一被験者内か、frame 単位か、がこの文にない。査読者が求めた
"4:1 training/validation split is performed randomly over frames, overload trials, and subjects."
に相当する情報がない。

[修正案]
以下を記述する。
・分割はフレーム単位である。
・3人の被験者それぞれでフレームの 4/5 を training、1/5 を validation に分ける。

4節「Experiment setup」subsection「Processing of proposed system」2段落目
修正前:
"Data were split 4:1 for training and validation; multi-scale grouping (MSG) formed PointNet++ groups."
修正後:
"We split frames of each of the three experiment participants at a ratio of 4:1."
  "Four fifths of the frames were used for training."
  "One fifth of the frames were used for validation."
"Multi-scale grouping (MSG) formed PointNet++ groups."

R.2-2
We have modified the description to state that the training and validation split was performed at the frame level.
We have modified the second paragraph in Section 4.4.
We made this modification because the unit of the 4:1 split was not clearly specified and reproducibility was insufficient.

(Second paragraph, Section 4.4)
We split frames of each of the three experiment participants at a ratio of 4:1.
Four fifths of the frames were used for training.
One fifth of the frames were used for validation.

C.2-3（原稿反映完了）
- Please explain whether validation data includes the same subjects as the training data.  Although the validation accuracy in Fig. 5 is nearly 100%, the test accuracy in table 2 is much lower and varies across subjects.
[原因]
validationに用いたデータが明示されていない。
査読者はvalidationがほぼ100%に対して、testの精度が低く被験者ごとにばらついている。そのため、trainingとvalidationが同じ被験者ではないかと推測している。

4節「Experiment setup」subsection「Processing of proposed system」2段落目
"Data were split 4:1 for training and validation;"
Dataが指しているのが学習データの3名なのかが不明。査読者は学習用3名のデータを分けたと判断した。

[修正案]
C.2-2の修正で対応可能

R.2-3
The modification in R.2-2 addresses this comment.

C.2-4（原稿反映完了）
- Although the current comparison shows which feature/clustering combination works better, it does not show whether the proposed feature extraction and clustering are necessary.
Please add at least one stronger baseline method, for example, pointnet++ using raw XYZ coordinates without additional features or PointNet/PointNet++ without clustering would be appropriate.
[原因]
比較は追加4特徴 × 3クラスタリング（None / DBSCAN / k-means）の12条件である。12条件はすべて追加特徴付きであり、raw XYZ入力の条件はない。12条件を比較の全体として出しており、raw XYZを置かない理由もない。Noneはクラスタリングなしであり、追加特徴なしではない。

4節「Experiment setup」subsection「Processing of proposed system」1段落目
"Processing followed Section 3: two vertices defined each person region for trimming; Open3D extracted normals, dimensionality features, proportion of variance, and FPFH."
（実験入力が4特徴だと書いてあり、raw XYZ条件も省略理由もない）

[修正案]
点座標のみは評価しないと追記する。理由は、既存研究で点座標と点特徴を併用した方が点座標のみより精度が高いことがすでに示されているため。

4節「Experiment setup」subsection「Processing of proposed system」1段落目
修正前:
"Processing followed Section 3.2: two vertices defined each person region for trimming; Open3D extracted normals, dimensionality features, proportion of variance, and FPFH."
修正後:
"Processing followed Section 3.2: two vertices defined each person region for trimming; Open3D extracted normals, dimensionality features, proportion of variance, and FPFH."
"We do not evaluate point coordinates only on the basis of the comparison in existing research \cite{DBLP:journals/corr/QiYSG17}."
  "The research evaluated point coordinates only and point coordinates with point features."
  "The research reported higher accuracy with point coordinates and point features than with point coordinates only."

R.2-4
We have added a qualitative justification based on existing research for not evaluating point coordinates only.
We have added three sentences in the first paragraph in Section 4.4.
We made this modification because existing research already reported the point-coordinates-only baseline. The fact was not stated in the manuscript.

(First paragraph, Section 4.4)
We do not evaluate point coordinates only on the basis of the comparison in existing research [21].
The research evaluated point coordinates only and point coordinates with point features.
The research reported higher accuracy with point coordinates and point features than with point coordinates only.
[21] C. R. Qi, L. Yi, H. Su, and L. J. Guibas, ‘‘PointNet++: Deep hierarchical feature learning on point sets in a metric space,’’ CoRR, vol. abs/1706.02413, 2017.

Additional comments:

C.2-5（原稿反映完了）
- the authors should be careful when writing the manuscript. For example, the author name is : "...Trovator" but the biography is "...Trovato". Which one is correct?
[原因]
論文冒頭　著者名・論文末尾 biography
査読者は著者名が"Trovator"となっており、biographyの"Trovato" が食い違っていると指摘。原稿上の著者名のスペルミス。

[修正案]
論文冒頭の著者リストを修正する。

修正前:
"GABRIELE TROVATOR"
修正後:
"GABRIELE TROVATO"

R.2-5
We have modified the author name from Trovator to Trovato.
We made this modification because the spelling of the author name did not match the biography.

(Author list)
GABRIELE TROVATO

C.2-6（原稿反映完了）
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

[修正案]
誤綴りと表記ゆれを直す。原稿全体も再校する。
・著者名 Trovator は C.2-5 に従う
・4.1 の見出し Expeirmental を Experimental にする
・biography の大学院名を Electrical Engineering and Computer Science に統一する

4節「Experiment setup」subsection「Experimental system」見出し
修正前:
"Expeirmental system"
修正後:
"Experimental system"

論文末尾 biography 1番目（Wataru Sano）
修正前:
"Graduate School of Electric Engineering and Computer Science"
修正後:
"Graduate School of Electrical Engineering and Computer Science"

論文末尾 biography 3番目（Haruma Shiraishi）
修正前:
"Graduate School of Electric Engineering and Computer Science"
修正後:
"Graduate School of Electrical Engineering and Computer Science"

論文末尾 biography 4番目（Ryusei Sugano）
修正前:
"Graduate School of Electric Engineering and Computer Science"
修正後:
"Graduate School of Electrical Engineering and Computer Science"

R.2-6
We have modified the subsection heading Expeirmental system to Experimental system. We have modified Electric to Electrical in the author biographies. 
We have modified the subsection heading in Section 4.1. We have modified the biographies of Haruma Shiraishi, and Ryusei Sugano.
We made this modification because typos and inconsistent English spelling remained in the manuscript.

(Subsection heading, Section 4.1)
Experimental system

(Biography of Haruma Shiraishi)
Graduate School of Electrical Engineering and Computer Science

(Biography of Ryusei Sugano)
Graduate School of Electrical Engineering and Computer Science

C.2-7（原稿反映完了）
- check again the reference, in section 2.1, the authors stated "... presented PointNet [11]. But the reference [11] is not the PointNet paper.
[原因]
PointNet の初出引用が PointNet 論文ではない。[11]は多クラス分類の指標解説である。PointNet++の論文は[21]である。

2節「Related works」subsection「Model architecture」2段落目
"Qi et al. presented PointNet [11]."
著者名は正しいが、引用が誤り。

2節「Related works」subsection「Model architecture」5段落目
"PointNet++ is adopted in the proposed system because hierarchical grouping extracts local geometry from sparse desk-region point clouds without voxelization [21]."
ここでの引用は正しくPointNet++の論文を引用している。

[修正案]
2節「Related works」subsection「Model architecture」2段落目
"Qi et al. presented PointNet [11]."
PointNet の初出引用を PointNet 論文に差し替える。

R.2-7
We have modified the citation of PointNet to the PointNet paper.
We have modified the second paragraph in Section 2.1.
We made this modification because the previous citation did not point to the PointNet paper.

(Second paragraph, Section 2.1)
Qi et al. presented PointNet [21].
[21] C. R. Qi, H. Su, K. Mo, and L. J. Guibas, ‘‘PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation,’’ CoRR, vol. abs/1612.00593, 2016.

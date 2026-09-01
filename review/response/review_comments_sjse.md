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


1. This study uses LiDAR to investigate movements of human hands. Whilst the introduction mentions the need to measure movements of human hands, it does not refers to the advantages of using LiDAR. Please add descriptions to justify the use of LiDAR for this objective.


2. The term ‘participants’ is used as subjests. Please revise to modify them to 'experiment participants’.


3. In section 4.1, the terms ‘A’ and ‘AB’ are used to refer to test data; these represent data from the experimental participants respectively. Plase add descriptions on how the authors acquired these test data before referring to them.


4. In Section 4.5 ‘Evaluation metric’, the classification models were trained using data obtained from three experimental participants; however, there are no descriptionis on how these three participants were selected. Please add details on the criteria of participants selection with the discussions on whether changing to other criteria would affect the results.


5. The positions of Figure 5 (c) ‘Proportion of variances’ and (d) ‘FPFH’ are reversed. Please swap them. In addtion, in discussions of these results, please clarify the level of accuracy that would be considered sufficient to indicate that the model has been sufficiently trained.


6. There are blank lines on the right-hand side of page 5. Please adjust the layout of the manuscript to remove them, such as moving 5.Conclusion to the page 5.


----------------------- REVIEW 2 ---------------------

SUBMISSION: 23
TITLE: Classification of postures of people with hand movement working in office environment by LiDAR sensor network

----------- Overall evaluation -----------
SCORE: 4 (conditional accept)
----- TEXT:
The paper addresses a meaningful problem: classifying fine-grained office desk-work states such as mouse operation, trackpad operation, typing, and sitting still using a LiDAR sensor network. The motivation is clearly stated. The paper also presents a real experimental system using multiple LiDAR sensors, point-cloud preprocessing, feature extraction, clustering, downsampling, normalization, and PointNet++ classification. The experiment includes training data from three subjects and test data from twenty-eight subjects, which gives some evidence of generalization beyond the training subject. The comparison of feature and clustering combination is useful (section 5.2 table 2).

However, there are some ambiguous desciprionts in the manuscript and also it lacks some key descprionts to show the benefits of the proposed method. Please revise the manuscript in the following points:

- Using accuracy alone as the evaluation metric is not sufficient. The four classes are fine-grained and likely to be confused with one another. For example, mouse vs pad operation. Pleased add a confusion matrix and results of class-wise precision, recall, F1 score for each preprocessing configuration.

- Section 4.4 states that: "data were split 4.1 for training and validation.
It should be correctly "4:1 training/validation split is performed randomly over frames, overload trials, and subjects." Please revise this expression to a correctv one.

- Please explain whether validation data includes the same subjects as the training data.  Although the validation accuracy in Fig. 5 is nearly 100%, the test accuracy in table 2 is much lower and varies across subjects.

- Although the current comparison shows which feature/clustering combination works better, it does not show whether the proposed feature extraction and clustering are necessary.
Please add at least one stronger baseline method, for example, pointnet++ using raw XYZ coordinates without additional features or PointNet/PointNet++ without clustering would be appropriate.

Additional comments:

- the authors should be careful when writing the manuscript. For example, the author name is : "...Trovator" but the biography is "...Trovato". Which one is correct?
- some typos and english grammar existed in the manuscript.
- check again the reference, in section 2.1, the authors stated "... presented PointNet [11]. But the reference [11] is not the PointNet paper. 

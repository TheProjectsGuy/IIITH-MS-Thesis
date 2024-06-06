# Response to the Thesis Evaluation

## Table of contents

- [Response to the Thesis Evaluation](#response-to-the-thesis-evaluation)
    - [Table of contents](#table-of-contents)
    - [Panel Comments - 5th June 2024](#panel-comments---5th-june-2024)
        - [Comments by Examiner 1](#comments-by-examiner-1)
        - [Comments by Examiner 2](#comments-by-examiner-2)

## Panel Comments - 5th June 2024

Recommendation by pg-chair: Proceed

Pushpalatha B Date: 05-06-2024 14:08:05

Further process from student:

1. If you haven't completed it yet, please share your plan for the public presentation. (Wednesday/Saturday – during 2:30 and 5:00 PM) ( Public presentation is not applicable for proposal thesis)
2. Thesis defense ( Viva, Proposal or final) will be scheduled on any day ie., Thursday / Friday / Saturday. The student will share at least 3 days of his/her availability, then office will accordingly check the dates with the panel to schedule defense date.
3. The student should complete his/her public presentation and thesis defense within a month of receipt of this email else should pay a semester fee which will be credited to STGC account.
4. Share response report with pgcell a week before the defense + Have one or more slides in the defense describing your response

### Comments by Examiner 1

**Overall Evaluation**: Suitable for MS

Extremely well written chapters 1 introduction and 2 foundation model; well done!

Just 3 comments:

- Paragraph before 3.2.1.3, Process, you mention selecting facet and layer based on inspection, but should rather be based on ablations (Fig 3.4) right?
- I missed one analysis; given the aggregated features, do the results change based on how the distances or similarities are computed between query and db images? How is this done currently?
- Table 3.8, and some other places, sometimes the comparison is unfair. ViT-G is a huge model, comparing it with ViT-B CosPlace and saying it's better would be expected right?

Can discuss these points during the defense, thanks

### Comments by Examiner 2

**Overall Evaluation**: May Accept

The thesis is poorly written. The continuity in reading the text is lacking.

The problem needs to be more clearly defined. What is the input? What is the expected output? What is the metric used?

The thesis claims to suggest that they have build a "Universal VPR system". Its important also to mention where the model fails.

There need to be a clear description why the model could be called a foundation model. What does it meant to be a foundation model for IR?? The database of the IR is always going to be limited and cannot contain all the possible images of the world? Foundation models are supposed to work without any modifications on a wide variety of scenarios (without even retraining). Its unclear in what sense the term is being used.

Why is a detailed survey of SLAM needed when the focus of the thesis is VPR or IR??

In table 3.8,3.9 it not mentioned what the units for the numbers are or what metric is being talked about.

Please address all these comments before the defense.

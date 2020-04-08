# Autonomous-Tagging-of-StackOverflow-Questions
## The Problem:
* We are given a dataset containing 10% of the questions on Stackoverflow, with Answers and Tags
* Given this dataset, we must build a predictive model predicting the tags for each new question encountered
* The predictive model(s) must have as high an accuracy as possible, given the dataset and it’s limitations

## The Data:
The dataset consists of 3 CSV files with the following formats:
* Questions:
 * Contains the title, body, creation date, closed date (if applicable), score, and owner ID for all non-deleted Stack Overflow questions whose Id is a multiple of 10.
** Has the format: Id, OwnerUserId, CreationDate, ClosedDate, Score, Title, Body
* Answers:
**Contains the body, creation date, score, and owner ID for each of the answers to these questions. The ParentId column links back to the Questions table.
** Has the format: Id, OwnerUserId, CreationDate, ParentId, Score, Body
* Tags 
** Contains the tags on each of these questions
** Has the format: Id,Tag

* The dataset can be downloaded at https://www.kaggle.com/stackoverflow/stacksample/data
* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Datasets

This dataset contains the annotations of toxicity evaluation on 120 online comments. 
We proposed a perspective taking annotation method in our paper and collected perspective annotations from female and male annotators through Prolific in 2022. 

#### comments.csv contains the information of online comments in our study.
- id: the ID of comment in our study.
- comment_id: the identifier of comment in the dataset [[1]](#1)
- text: the text of comment
- pos_f: the aggregated toxicity rate (ground truth) of female annotators in the pilot study.
- pos_m: the aggregated toxicity rate (ground truth) of male annotators in the pilot study.


#### formal_annotations.csv contains the collected human annotations in the formal experiment.
Features:
- workerId: the identifier of annotators on Prolific. To protect the identity of annotators, we replace their identifiers with randomly generated strings.
- comment: the ID of comment in our study.
- answer_f: the perspective-taking annotation when the annotator takes female perspectives.
- answer_m: the perspective-taking annotation when the annotator takes male perspectives.
- race: the annotator's race. 
* American: American Indian or Alaska Native
* Asian: Asian
* Black: Black or African American
* Hispanic: Hispanic or Latino
* White: White
* Others: Other races
- age: the annotator's age. 
- gender: the annotator's gender. We only recruited female or male annotators in our study.
- political: the annotator's political affiliation (Democrat, Republican and Independent).

#### pilot_females.csv contains the collected annotations from **female** annotators in the pilot study. 
- workerId: the identifier of annotators on Prolific. To protect the identity of annotators, we replace their identifiers with randomly generated strings.
- comment: the ID of comment in our study. 
- answer: the annotations of female annotators in the pilot study. 1: toxic -1: non-toxic.

#### pilot_males.csv contains the collected annotations from **male** annotators in the pilot study. 
- workerId: the identifier of annotators on Prolific. To protect the identity of annotators, we replace their identifiers with randomly generated strings.
- comment: the ID of comment in our study. 
- answer: the annotations of male annotators in the pilot study. 1: toxic -1: non-toxic.

#### Reference
<a id="1">[1]</a> 
Chris J Kennedy, Geoff Bacon, Alexander Sahn, and Claudia von Vacano. 2020. 
Constructing interval variables via faceted rasch measurement and multi-task deep learning: a hate speech application. arXiv preprint arXiv:2009.10277.



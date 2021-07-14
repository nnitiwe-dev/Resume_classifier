# Resume_classifier
Resume Classification  is a project that builds a model to sort candidate CVs and predict candidates invited for an Interview and candidates not invited. 

## Data Source
Resumes in this dataset were queried from Indeed.com with keyword ```'data scientist', location 'Vermont'```. It contains a total of 125 Resumes (33 invited for the Interview and 92 Candidates not invited). If a resume is 'not flagged', the applicant can submit a modified resume version at a later date. If it is 'flagged', the applicant is invited to interview.

Source:  https://www.kaggle.com/samdeeplearning/deepnlp

## Results
The Naive Bayes Classifer model score a weighted average 
![Confusion Matrix](https://miro.medium.com/max/1200/0*-oGC3SE8sPCPdmxs.jpg)


| |Metrics| Score|
|---|---|---|
|1. |**Precision** |  76% | 
|2. |**Recall** | 76% |
|3. |**F1-Score** | 74% | 

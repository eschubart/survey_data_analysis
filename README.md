This script consists of the analyses run on survey data (both open-ended and closed-ended questions), chat data from the “Ask ARU” chat spaces of Welcome Buddies and their assigned new student cohort, and demographic data all collected by the Student Experience Team at ARU. Sentiment analysis is applied (both supervised and unsupervised) on open-ended exit survey questions from new students. These scripts interrogate possible correlations and/or associations between Welcome Buddy performance scores and relevant demographic characteristics, analyse chat data from the “Ask ARU” chat spaces of Welcome Buddies and their assigned new student cohort for formality, warmth and helpfulness metrics and conduct sentiment analysis (both supervised and unsupervised) on open-ended exit survey questions from new students. Results indicate a high level of student satisfaction with the Welcome Buddy scheme. Results also indicate that high Welcome Buddy performance is significantly associated with Welcome Buddies who are female, older, and engage in informal, highly helpful and warm communication within their chat spaces. These findings demonstrate the utility of supervised and unsupervised sentiment analysis, descriptive statistics, and regression models in evaluation of student ambassador schemes at universities. The written dissertation can be found attacged as a pdf file within this repository.

The "student respondents" file consists of the analyses run on the exit survey data (both open-ended and closed-ended questions) collected by the Student Experience Team at ARU, "demographic" contains all analyses run on demographic variables of Welcome Buddies, including the assignment of formality, warmth, and helpfulness scores to chat space communications, and "sentiment analysis" contains the three different types of sentiment analyses run on one of the open-ended survey questions. The first sentiment analysis was run with a pre-trained DistilBERT model, the second sentiment analysis was achieved by first embedding the text with a word2vec model and then clustering the vectors with a k-means clustering algorithm. The last sentiment analysis was achieved by manually assigning each sample as positive (1) or negative (0), vectorizing the text with a TF-IDF vectorizer and then classifying the sentiments with a logistic regression model.

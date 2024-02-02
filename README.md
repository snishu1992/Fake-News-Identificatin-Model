Fake News Classification Model: Analysis and Implementation

Prepared by

Prashant Singh

for

House Of Couton Private Limited (Test)

Abstract:

The proliferation of misinformation on social media platforms presents a pressing
challenge, with diverse entities such as organizations, politicians, individuals seeking
personal gain, and certain news media outlets contributing to the dissemination of fake
news. Ascertaining the authenticity of online news remains a complex task, marked by the
inherent limitations of manual classification—tedious, time-consuming, and susceptible to
bias. Addressing this escalating issue necessitates the development of tools focused on
the detection, classification, and mitigation of fake news to safeguard against the distortion
of events, manipulation of public perception, and potential consequences on decision-
making processes.

Methodology:

The decide under which category the news article comes under (whether it is
untrustworthy and false news or real).
The first step, which is text preprocessing was performed using the following:

 Taking care of null/missing values

 Feature extraction

 TfidfVectorizer

 Wordcloud

 Matplotlib

 Naive Bayes Model

For feature engineering, the TF-IDF technique is used. This processed data is provided as
an input to Machine learning models, where the data is made to fit the model, to get a
prediction as an output.

Table of Contents (Code)

1. Import Data and Inspect
2. Text Cleaning
3. Vectorization
4. Train and Test Split
5. Model Training
6. Accuracy Test

Conclusion:

This code focused on the task of text classification within the context of a news collection
dataset. The project encompassed data exploration, text preprocessing, feature
engineering, and model training. Notably, it provided an opportunity to assess the
performance of selected machine learning algorithm on the given task.
The results indicated that the Naive Bayes Model, coupled with TF-IDF vectorization,
demonstrated the high accuracy in categorizing newspaper articles into predefined topics.
This achievement highlights the potential of this approach for similar real-world
applications in the domain of new articles or text classification in general.
It&#39;s important to recognize that text classification tasks often involve ongoing refinement
and exploration. Further enhancements, such as hyperparameter tuning and advanced
modeling techniques, could be explored to further improve classification performance.

References:

1. Kaggle (2022). Kaggle: Your Home for Data Science. [online] Kaggle.com. Available at:
https://www.kaggle.com/.
2. GitHub. (2019). MahanPourhosseini - Overview. [online] Available at:
https://github.com/MahanPourhosseini/ [Accessed 1 Feb. 2024].

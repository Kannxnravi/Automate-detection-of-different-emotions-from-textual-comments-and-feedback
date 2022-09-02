# Automate-detection-of-different-emotions-from-textual-comments-and-feedback
RIO45 - Automate detection of different emotions from textual comments and feedback


Project Description:
---
**Project Objective & Brief**: To develop a deep learning algorithm to detect different types of emotions contained in a collection of English Sentences or a large paragraph.


#### Project Guidelines:
1. Identify & finalize a collection of English sentences or a large paragraph which will also cover contradictory statements.
2. Develop a deep learning model for detection & segmentation of emotions whether positive, negative, or neutral from the paragraph.
3. Test the model accuracy.

#### Expected Project Outcome:
1. Algorithms to detect different types of emotions from a paragraph or a sentence.
2. Detailed presentation with proof of reasonable accuracy.

#### Software Requirements to Implement the Project:
1. Google Collab
2. Python, Java (opt.), Eclipse, Ubuntu OS (opt.)


Emotion Analysis:
   - Analyze textual feedback to the level of reading between lines.
   - Categorizing feedback & analyzing its emotion by picking up words,contexts,patterns,behaviours.This can be even taken to the level of individual's expressive capability of a particular situation.

Approaches to Text Classification
---
* **Rule Based Systems:**
 1. Rule-based approaches classify text into organized groups by using a set of linguistic rules.
 2. Each rule comprises of a pattern based on semantics and its predicted category.
* **Machine Learning based Systems:**
 1. Text classification based on past observations.
 2. By using training data, the algorithm can learn the different associations between pieces of text and that a particular output (i.e. tags) is expected for a particular input (i.e. text).
 3. Feature extraction: Transforms each text into a numerical representation in the form of a vector. E.g. bag of words [a vector represents the frequency in a predefined dictionary of words ]
 4. The algorithm is fed with training data consisting of feature sets.
 5. Once trained with enough training samples, the machine learning model can begin to make accurate predictions on unseen text with similar feature sets.

Text Classification Algorithms
---
Some of the most popular machine learning algorithms for creating text classification models include the naive bayes family of algorithms, support vector machines, Regressions, and deep learning algorithms with CNN and RNN. Metrics and Evaluation Cross-validation is a common method to evaluate the performance of a text classifier.
 1. It consists in splitting the training dataset randomly into equal-length sets.
 2. For each set, a text classifier is trained with the remaining samples (e.g. 75% of the samples).
 3. The classifiers make predictions on their respective sets and the results are compared against the human-annotated tags.
 4. With these results, a performance metrics is built, that are useful for a quick assessment on how well a classifier works.
 
 Metrices & Evaluation:
 ---
    - It consists in splitting the traing set randomly into equal-length sets.
    

Stages In Classification:
---
   - Load EDA Packages(Exploratory Data Analysis)
   - Load Data via Packages
   - Load Text Cleaning Packages
   - Load Machine Learning Packages
       -->Estimators
       -->Transformers
   - Load Dataset
   - Value Count
   - Plot
   - Data Cleaning
   - User Handles
   - Stopwords
   - Features & Labels
   - Split Data
   - Build Pipeline
   - LogisticRegression Pipeline
   - Train and Fit Data
   - Check Accuracy
   - Make A Prediction
   - Prediction Prob
   - To Know the classes


Data Sources to solve problem
---
* Data Sets from any open source data sources can be used. Model building and solution engineering is NOT restricted to data.
* Example:
 1. https://paperswithcode.com/task/emotion-classification
Some Of the Datasets:
---
 1. https://ai.stanford.edu/~amaas/data/sentiment/
 2. https://data.world/crowdflower/sentiment-analysis-in-text
 3. https://www.kaggle.com/crowdflower/twitter-airline-sentiment

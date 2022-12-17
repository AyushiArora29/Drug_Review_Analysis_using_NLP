<h1>Functional Analytics Project on Drug Review Dataset using NLP</h1>
<p>By Ayushi Arora, Yogesh Sachdeva and Arpit Govila</p>
<h2>Introduction</h2>
<p>In this project we tried to explore and visualize the Drug Review Dataset using NLP and Hugging Face transformers to do the sentiment analysis</p>

# About Dataset

* The Drug Review Dataset is taken from the UCI Machine Learning Repository. This Dataset provides patient reviews on specific drugs along with related conditions and a 10-star patient rating reflecting the overall patient satisfaction. The data was obtained by crawling online pharmaceutical review sites. The Drug Review Data Set is of shape (161297, 7) i.e. **It has 7 features** including the review and **161297 Data Points** or entries.
* The features are 'drugName' which is the name of the drug, 'condition' which is the condition the patient is suffering from, 'review' is the patients review, 'rating' is the 10-star patient rating for the drug, 'date' is the date of the entry and the 'usefulcount' is the number of users who found the review useful.


### Attributes :
1. **drugName :** name of drug
2.**condition :** name of condition
3. **review :** patient review
4. **rating :** 10 star patient rating
5. **date :** date of review entry
6. **usefulCount :** number of users who found review useful

# Objective :

#### The Objective of this Project is to Analyse the Dataset, plot the inferences with good visualizations and answer some Questions to extract information from the Dataset.
#### Also analyse the sentiment of the drug Users, according to their reviews and various other features like the condition they are suffering from, the rating of the drug used, Date of the usage, and others.


#### *Questions*
+ Types of questions we can ask?(Drugs,Review,Rating,Conditions,Time,Genuiness,etc)
+ What is the most popular drug?
+ What are the groups/classification of drugs used?
+ Which Drug has the best review?
+ How many drugs do we have?
+ The number of drugs per condition
+ Number of patients that searched on a particular drug
+ How genuine is the review? (Using sentiment analysis)
+ How many reviews are positive,negative,neutral?
+ Correlation between rating and review and users who found the review useful
+ Can you predict the rating using the review?
+ Distribution of rating
+ Amount of review made per year and per month
+ Which condition has the most review on drugs



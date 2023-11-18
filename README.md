# Module20Capstone
Initial Report and EDA
Investigation Question:
What level of accuracy can we expect from an NLP model when classifying news articles into different categories? Is this level of accuracy sufficient to replace human classification?
Dataset Table:
News Category Dataset (kaggle.com)
In the dataset each news or record in the dataset consists of the following attributes:
•	category: category in which the article was published.
•	headline: the headline of the news article.
•	authors: list of authors who contributed to the article.
•	link: link to the original news article.
•	short_description: Abstract of the news article.
•	date: publication date of the article.

Technique:
Natural Language Processing

Expected Results:
The model will assess both the headline and the short description of the article to identify which one yields superior accuracy in determining the news category.

Importance:
This model will simulate a real-world scenario where manufacturing events are categorized for trend analysis. Due to confidentiality constraints, actual data cannot be shared, so this dataset serves as a representative example of a similar problem and approach. The benefits for the project is eliminate the human intervention of assessing every month more that 50 manufacturing events to classify them

Code Description
This NLP model will read the headline of the article and based on that information determine the category. The score metric use was precision, this model is replicating an actual real application problem. The interest is to understand how capable the model is by different target categories and its overall performance. This due to the fact that the sample will not be equally distributed by category. 

The NLP steps followed were Tokenization, Normalization and Feature extraction, and apply Multinomial Naive Bayes classifier
The overall precision of the model was 65%





# Sentiment-Analysis-using-e-commerce-data


## Problem Statement

One of our clients abc.com is one of the World's leading E-commerce marketplaces and is headquartered in the US. The company initially started as an online bookstore. Later, it expanded its product line to include the sale of mobile phones, electronics, household appliances, clothing, and consumables. On their website, they provide a wide range of products from various manufacturers. However, they have suddenly become aware that their items are receiving fewer evaluations. Additionally, the majority of individuals are commenting on the product in both favorable and negative ways. As a result, people want to know where they fall short. Is it the product quality, logistics, cost, or the response of the customer service representative? However, because they operate a global business, it is impossible for them to read all of the comments for all of the products. Additionally, locals are free to comment on their own languages.

They made the decision to employ a data scientist for this project so that they could better understand customer feedback. Khalimama.com sought to analyze sentiment and extract information from reviews written in several languages. Reviews from the dataset are available in English, German, Spanish, French, Japanese, and Chinese. The dataset's "review id, product id, reviewer id, stars, reviewer body, review title, the language, and product category (for example, "books" or "appliances")" are all included in each row.

There is a total of 200,000 reviews in the dataset. A product may only receive a maximum of 20 reviews, and a reviewer may only submit a maximum of 20 reviews per reviewer. Every review is cut off after 2,000 characters and must have at least 20 characters.

Please note that reviews are written in a language that may not be the same as their target audience (e.g. reviews from amazon.de are primarily written in German, but could also be written in English, etc.). We used a language detection algorithm to ascertain the language of the review text for this reason, and we eliminated reviews that weren't written in the anticipated language.

Considering that this is an unsupervised machine learning assignment. Here, we must make predictions about each record's class based on its sentiment. How "Positive/Negative/Neutral" the record is. Our model should eventually be able to predict the classes for each record (0,1,2).

Here, We are taking a sample of 1000 records for our model building and training.

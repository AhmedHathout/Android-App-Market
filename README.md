# Android App Market

Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this Project, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. we'll look for insights in the data to devise strategies to drive growth and retention.

This Project is about applying the skills from [Manipulating DataFrames with pandas](https://www.datacamp.com/courses/manipulating-dataframes-with-pandas) and [Python Data Science Toolbox (Part 1)](https://www.datacamp.com/courses/python-data-science-toolbox-part-1).

The data for this Project was scraped from the Google Play website. While there are many popular datasets for Apple App Store, there aren't many for Google Play apps, which is partially due to the increased difficulty in scraping the latter as compared to the former. The data files are as follows:

* `apps.csv`: contains all the details of the applications on Google Play. There are 13 features that describe a given app.

* `user_reviews.csv`: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.

The main things we do in this project are:-
* cleaning the data
* exploring app categories.
* examining the distribution of app ratings
* examining the relation between the price of an app and its price
* examining the relation between the price and category of each app
* filtering out junk apps
* examining how popular paid apps are and compare it with the popularity of free apps
* sentiment analysis

Also there is a small presentation of some of the results we found in this repository

---
layout: post
title: News Awareness of Filipinos in Social Media
subtitle: Machine learning with the use of Ridge Regression and TFIDF
gh-repo: soadleirbag/eskwelabs-capstone-filipino-newstweets
gh-badge: [star, fork, follow]
tags: [Esklwelabs, Capstone, Machine Learning]
comments: true
header-img: https://github.com/soadleirbag/soadleirbag.github.io/blob/master/img/capstone-images/sona_vs_bjg.PNG?raw=true
---

This capstone project deals with analyzing where the attention of the Filipino people lie with regards to the news tweets being published daily. Ridge regression was used to make the predictions of a tweet's performance (Likes & Tweets) from tweets that were converted to TFIDF vectors.



### How the project came to be

![sona_vs_bjg](https://github.com/soadleirbag/soadleirbag.github.io/blob/master/img/capstone-images/sona_vs_bjg.PNG?raw=true){: .center-block :}

As a daily social media user in the Philippines, I noticed that the Bea, Julia, and Gerald scandal (A scandal between these celebrities in our country) took over social media on the same week that our President gave his State of the Nation Address. Despite having lots of nationwide issues brought up in that SONA, people were more concerned about who cheated on whom between the 3 celebrities I mentioned earlier.

Because of the scenario that happened, I wanted to explore this hypothesis:

## Filipinos are interested in celebrities than social issues that the country has.

By exploring this hypothesis, we'll figure out by using machine learning how we can get Filipinos more engaged with the relevant problems in the Philippines.

![hootsuite](https://github.com/soadleirbag/soadleirbag.github.io/blob/master/img/capstone-images/hootsuite.PNG?raw=true){: .center-block :}

Based from a recent statistic made last January 2019, roughly 61% of Filipinos that are using social media are on the ages of 18 - 34. We now live in a age where people would tune into their smartphones to get the latest news updates instead of their television. This is why I'll be using **Twitter** as a medium for this study.

In order to confirm the hypothesis, we'll need to answer these three questions in order to understand what's currently going on in social media.

1. What are the top news tweets of 2019 based from likes & retweets?

2. What are the similarities of the popular news tweets?

3. Can we predict how popular a tweet will be based from the features it has?


![methodology](https://github.com/soadleirbag/soadleirbag.github.io/blob/master/img/capstone-images/methodology.PNG?raw=true){: .center-block :}

In order to answer the questions earlier, this is the methodology that I went through. I'll be posting a separate post on how I did web scraping on Twitter.

## 1. Which news tweets has gathered most of the Filipino's attention this 2019

{: .box-note}
**Note:** Data is only until September 2019 since that's when the project was done.

![methodology](https://github.com/soadleirbag/soadleirbag.github.io/blob/master/img/capstone-images/distribution.PNG?raw=true){: .center-block :}

To give a brief overview, these are the total number of tweets that was gathered from each news source I web scraped from in Twitter. This is just to show that the data is not skewed to one news source in this data analysis.

### President Duterte and other National News Headlines are consistently present each month

![word_cloud_freq](https://github.com/soadleirbag/soadleirbag.github.io/blob/master/img/capstone-images/word cloud freq.gif?raw=true){: .center-block :}

If we're going by frequency of tweets, President Duterte gets the most coverage out of all the topics this past year. These tweets about President Duterte are followed by national news headlines like the elections, storm warnings, Catriona Gray, China, and etc.

![top_tweets](https://github.com/soadleirbag/soadleirbag.github.io/blob/master/img/capstone-images/top_tweets.PNG?raw=true){: .center-block :}

But if we're going to base it by likes, most of the top news tweets involves at least a popular figure in the Philippines. Its also good to note that most of the top news tweets come from ABS-CBN (A popular celebrity centric TV network in the Philippines.)

## 2. How are these popular tweets similar to one another?
**like what features do they have that gives them attention**

## 3. Can a machine learning model predict a tweet's performance?
**Based from what's established from the 2 questions before.**















#--------------------------------------------------
## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .center-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

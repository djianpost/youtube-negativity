---
layout: page
title: Negativity on YouTube
subtitle: Alice's path to become a famous YouTuber
gh-repo: djianpost/youtube-negativity
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---


_Dear reader, let me tell you the story of the collaboration of Alice, a Youtuber apprentice, and of ADAGANG, a talented group of Data Analysists. The meeting pushed the team to dig into YouNiverse data sets to try to answer an interesting question of the young girl. You have the chance to have access to the communication they exchanged and learn all the secrets the group discovered for Alice.

_It all started on a normal lazy Sunday evening for the Team ADAGANG. The friends gathered in front of a show, and the evening was slowly coming to an end. Suddenly, they received an intriguing mail.

# Alice's email
Hello ADAGANG, 
I’m Alice. I am a big fan of YouTube. I kind of have developed a passion for the creation of videos and I thought that I should try myself to make a place in the YouTube game. Unfortunately, I have rapidly realized that it was not easy as it seemed. I have also noticed that I am rather lazy, and I would like to know the different tricks I could use to maximize my success on the platform without spending too much time working. And I suddenly had an idea!
With Youtube’s and Internet’s user experience, I have noticed that people are often saying that using a negative content can gather more attention. In fact, people are often speaking about Click-Bait. This term being quite sketchy and difficult to determine really, I am mostly interested in negativity. Can negativity bring me fame on YouTube?
Please ADAGANG, I have heard about your talents, and I am sure that this question is so easy for to answer. I am going to pay you well!

Waiting for, I hope, an interesting and full of secrets answer from your side, I send you my best regards,

Alice, the lazy Youtuber

# ADAGANG answer
Dear Alice,
Your email really aroused our curiosity. We hesitated to accept your offer because your motivation is far from being lofty. You should rather work for your dreams to happen!
However, your cheque is so full of zeros that a negative answer was difficult to give (Matteo needs in fact a new car…). We decided then to accept this project! You can find in the following the final report about your interrogations. To conduct this study the video’s title, description and tags has been analyzed. Sentiment analysis, most used words and topic research have been performed in order to determine how emotions are linked to successful videos. The study is conduct on short and long term and investigates whether negative content is a more effective strategy in some fields (e.g. politics, science) than others (e.g. recipes).

Hoping that you will be able to reach your goal,
Best regards,

ADAGANG, the talented group of Data analysists

# The YouNiverse dataset
To answer your question, we used the YouNiverse dataset. This huge data (over 100GB!) contains a lot of information about the videos and channels statistics through time. For practical reasons, the analysis is performed on only one year (2019). Additional datasets about the American trending videos from 2017 to 2018 and from 2020 to 2022 are also used.

# What is negativity?
So, we are bringing an answer to determine if negativity makes success. However, without a precise definition, negativity can be difficult to represent. Throughout this project, we have used a sentiment analysis. In fact, a sentiment intensity analysis has been performed on the titles and descriptions of the videos. A score of negativity, positivity and neutrality is computed and used to determine how linked success and emotions are on YouTube.
To represent in a better way what returns the sentiment intensity analysis, some examples are presented in the following:


The examples illustrate what is linked with a highly negative or positive score obtain with the sentiment intensity. Throughout this data story the videos and channels are analyzed with this sentiment score.

# First step of the analysis
Alice, we agree with you. We have also heard more than once that negativity can gather more attention on a content. However, to make sure that the following analysis was worth it, we had to verify that a difference in negative sentiment intensity score can be highlighted between the videos that make success on YouTube and the videos that do not. To do so, the trending videos dataset has been used. Videos that reach the trends can be considered as successful. In addition, the number of views and likes are the most observable and relevant factors that are considered in the YouTube’s algorithm to propel a video in the trends. Of course, this is far from being the only reason for a video to become a trending video. This is, however, an assumption that has been made to filter the successful and not successful videos of our dataset. This first chapter do not lead to any results. This assumption is acceptable.

This figure shows clearly the difference of negative sentiment intensity between the videos that are successful and the ones that are not. This difference is observable in the titles and the descriptions. Obviously, the differences between the two groups are not big but they are statistically significant as the 95% confidence interval around the mean value is small. There are not overlap between the intervals of the two group. The difference is not negligeable. Of course, a lot of other factors could cause this difference, but it is not the point of this section. This observation justifies the following analysis.



_Ok, but _

regression 


_That's great, I'll make positive/negative videos. But what shall I speak about? Tell me more about what those successful negative videos talk about._

wordclouds



![wordcloud-education](assets/img/wc_Education.png){:class="img-responsive"}

{:.image-caption}
*Education*


![wordcloud-entertainment](assets/img/wc_Entertainment.png){:class="img-responsive"}

{:.image-caption}
*Entertainment*


![wordcloud-howto-and-style](assets/img/wc_Howto_and_Style.png){:class="img-responsive"}

{:.image-caption}
*Howto & Style*


![wordcloud-pets-and-animals](assets/img/wc_Pets_and_Animals.png){:class="img-responsive"}

{:.image-caption}
*Pets & Animals*




_Can you be more precise? What are the topics?_

topic extraction

{% include topics.html %}


_channel evolution_

channel evolution


_But in the end, is negativity really a good way to make success?_

explanations about the size of the effect




This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

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

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

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

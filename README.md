# Project 3 - Web APIs & Classification

## Problem Statement


IDEAL

Develop a model to analyse text in a reddit post and determine its source. It will have either come from the datascience or analytics subreddit. The idea is to find out whether self classification by users can determine whether the two groups have distinctive language based on what they post.

REALITY

There is a lot of debate as to whether there is a difference between a data scientist and an analyst. The roles do have some overlap in terms of tools used, type of work and they way some people perceive each role. Even role titles in companies are different and no definitive defintion exists. 

CONSEQUENCES

If the model is unsucessful then it will add weight to the argument that the disciplines are the same. If the model is not conclusive it will mean that even in self classifing groups, the language and topics which are discussed are indistinguishable to even advanced NLP models which are not biased by subjective factors. 

This will make it harder for employers, employees and education providers to claim that such a split exists and may have to tailor their approach accordingly.

PROPOSAL

I will scrape the data using the reddit API. I will bring back the posts and also the first layer of comments. This is to make sure I have enough data. After analysing the data I will make a baseline model and a first run of the model. I will then refine the model by using techniques such as lemmatising, adding more data and try to improve its accuracy score.

I will compare Logistic regression, Mulitnomial Naive Bayes and use the TF-ifd and CountVectoriser vectorisers.  After choosing the model and optimising it I will look to see what is driving the model and try and infer key words which drive any distinction. It will allow me to drive appropriate conclusions from there.

Success may not be a high score from the test. If there is no difference between the two roles then it is likely that the score will be low. This would also be important to know. Similarly a score above 70% on the model would be useful as I can conclude that differences do exist. The model should also be able to provide me with key insights into what is driving the model and explain the differences between the two sub reddit groups.



## Executive Summary


I have created a model to distinguish between a data scientist and an analyst just by looking at the text they use. The model is accurate and provides key insights into what the two groups discuss.

Data science and analytics have been used interchangably in the past causing confusion to employees, employers and training providers. However by training an NLP model from reddit posts it has detected key features and differences between the two which 
can be useful.

The model shows that data science is more technical and builds tools from the ground up. Analytics users more off the shelf software to allow them to use existing data and quickly create actionable business insights.

Some key words for data science are machine learning, data engineering, python, data visualisatin and web applications. Key analytics words include google analytics, data form, data warehouse, google optimise and Adobe analytics.

Now employees can classify their jobs better, employees can better determine what job interests them and training providers can run appropriate courses.



## Definitions and reddits

Reddit datascience: [link](https://www.reddit.com/r/datascience/)
"A place for data science practitioners and professionals to discuss and debate data science career questions."

Reddit analytics: [link](https://www.reddit.com/r/analytics/)
"Dedicated to web analytics, data and business analytics. We're here to discuss analysis of data, learning of skills and implementation of web analytics."

What is Data Science?

> Data science continues to evolve as one of the most promising and in-demand career paths for skilled professionals. Today, successful data professionals understand that they must advance past the traditional skills of analyzing large amounts of data, data mining, and programming skills. In order to uncover useful intelligence for their organizations, data scientists must master the full spectrum of the data science life cycle and possess a level of flexibility and understanding to maximize returns at each phase of the process.

source: [Berkeley](https://datascience.berkeley.edu/about/what-is-data-science/)


What is Data analytics?
> Data Analytics the science of examining raw data to conclude that information.

> Data Analytics involves applying an algorithmic or mechanical process to derive insights and, for example, running through several data sets to look for meaningful correlations between each other.

> It is used in several industries to allow organizations and companies to make better decisions as well as verify and disprove existing theories or models. The focus of Data Analytics lies in inference, which is the process of deriving conclusions that are solely based on what the researcher already knows.

source: [Simplilearn](https://www.simplilearn.com/data-science-vs-big-data-vs-data-analytics-article)



## References
[What’s the Difference Between Data Analytics and Data Analysis?](https://www.getsmarter.com/blog/career-advice/difference-data-analytics-data-analysis/)

[About stemming, lemmitization and stop words](https://www.datacamp.com/community/tutorials/stemming-lemmatization-python)

[What’s the Difference Between Data Analytics and Data Analysis?](https://www.getsmarter.com/blog/career-advice/difference-data-analytics-data-analysis/)

[What is Data Science? 8 Skills That Will Get You Hired in Data](https://blog.udacity.com/2014/11/data-science-job-skills.html)







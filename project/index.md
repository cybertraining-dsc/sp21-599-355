# Project: Chat Bots in Customer Service

* :o2: Author missing
* :o2: No need to use striikout for us, but you can use it for yourself
* :o2: Abstract should be defined by now
* :o2: Introduction is missing
* :o2: Refernces shoudl be defined by now


[![Check Report](https://github.com/cybertraining-dsc/sp21-599-355/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/sp21-599-355/actions)
[![Status](https://github.com/cybertraining-dsc/sp21-599-355/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/sp21-599-355/actions)
Status: in progress, Type: Project


Anna Everett, [sp21-599-355](https://github.com/cybertraining-dsc/sp21-599-355/), [Edit](https://github.com/cybertraining-dsc/sp21-599-355/blob/main/project/index.md)

{{% pageinfo %}}

## Abstract

Automated customer service is a rising phenomon for buisnesses with an online presence. As customer service bots advance in complication of problems they can handle one concern about the altered customer experiece is how the information is conveyed. Using customer support data tweets on twitter I run sentiment analysis on it customer tweets and then train a convolutional neural network to examine if conversation tone can be detected early in the conversation.

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

1. Introduction 
2. Procedure

    * The Dataset 
    * The Algorithm

3. Results 
4. Discussion 
5. Conclusion

**Keywords:** AI, chat bots, tone, nlp, twitter, customer service. 

## 1. Introduction

Please not ethat an up to date version of these instructions is available at

* <https://github.com/cybertraining-dsc/hid-example/blob/main/project/index.md>

Here comes a convincing introduction to the problem

Due to the rise of automation in businesses a lot of what is being seen by the general public is their use of chat bots in customer service. A chatbot is a software that is able to communicate with humans in real time in response to questions or sentences[^2].

However, a concern for companies using chat bots is the communication and interaction with the humans on the other end of the bot. Bots are convenient because they don’t need to have off hours, making customer service available 24/7, and are capable of providing quick responses. 

But most bots are limited in their ability to engage with the customers due to the necessity of generatability in the solutions.


## 2. Procedure


### 2.1 The Dataset

The dataset being used is from the kaggle online database and is called "Customer Support on Twitter"[^3]. 
This dataset has been chosen because it is the most well suited for tone detection and monitoring. Because of Twitter's informality as a social media platform, conversations are more likley to be of natural and causal speech patterns[^3].
In addition to this, the character limit imposed by the platform, 140 characters per tweet, both customers and company agents are required to give the most amount of information in the briefest amount of time. This should make it eaiser to detect and track tone. 

### 2.2 Pre Existing Efforts 

On the website from which my datset has been made available users often submit their own code working with that particular dataset. For the dataset that has been chosen most of the corresponing uploaded code is related to the pre-processing stage. 

TODO

### 2.3 The Algorithm

We will be using a recurrent neural network which has been found to be a common method used when dealing with natural language processing.

TODO

## 3. Using Images

![Figure 1](https://github.com/cybertraining-dsc/fa20-523-314/raw/main/project/images/chart.png)

**Figure 1:** Images can be included in the report, but if they are copied you must cite them[^1].

## 5. Datasets

Datasets can be huge and GitHub has limited space. Only very small datasets should be stored in GitHub.
However, if the data is publicly available you program must contain a download function instead that you customize.
Write it using pythons `request`. You will get point deductions if you check-in data sets that are large and do not use
the download function.

## 6. Benchmark

Your project must include a benchmark. The easiest is to use cloudmesh-common[^4].

## 7. Conclusion

TODO

## 8. Acknowledgments

Please add acknowledgments to all that contributed or helped on this project.
TODO

## 9. References

[^1]: Asbjørn Følstad, Cecilie Bertinussen Nordheim, Cato Bjørkli; What Makes users Trust A Chatbot for Customer Service, [online research paper] <https://www.researchgate.net/publication/327839749_What_Makes_Users_Trust_a_Chatbot_for_Customer_Service_An_Exploratory_Interview_Study>

[^2]: Chat bot statistics, [online source] <https://www.superoffice.com/blog/live-chat-statistics/>

[^3]: Kaggle, Customer Support on Twitter, [online resource] <https://www.kaggle.com/thoughtvector/customer-support-on-twitter/code>

[^4]: Gregor von Laszewski, Cloudmesh StopWatch and Benchmark from the Cloudmesh Common Library, [GitHub] <https://github.com/cloudmesh/cloudmesh-common>

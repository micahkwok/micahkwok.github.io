---
layout: post
title: False Positives
---


# What are False Positives?

I recently came acrosst this news [article](https://www.cbc.ca/news/canada/newfoundland-labrador/makkovik-false-positive-relief-1.5922781) titled: 
>False positive in Makkovik was ‘huge sigh of relief’ but shows how quickly COVID-19 can take hold

Seeing this, I thought it’d be a good time to teach or remind people of what a false positive (along with its closely related sibling, false negative) is and the impacts of it.

We’ll use COVID-19 detection tests to learn about this concept of false positives and false negatives, but before that let’s take a step back.
Let’s simply consider how we can measure a test. In its simplest form, a test can either be right or wrong. Whether the test is right, depends on if the test result matches if the has COVID-19 or not. So this means, there are actually two ways for a test to be right and two ways for a test to be wrong, leading us to have this nice little table below.

![matrix](img/FP_matrix.png)

It may look a bit confusing at first but we’ll go through these results individually.

#### How a test can be right:

- **True Positive**

    Starting in the green block labeled true positive. This is one of the two ways a COVID-19 test can be right. When the test predicts positive (saying that the tester has COVID-19) and the reality is that the tester is positive (tester actually has COVID-19), then the test worked and is right! This is known as a True Positive (TP). 

- **True Negative**

    Now let’s jump over to the other green block labeled true negative. The other way a COVID-19 test can be right is when it predicts negative (saying that the tester does not have COVID-19) and the reality is that the tester is negative (tester really does not have COVID-19). Again, the test worked and is right! This is known as a True Negative (TN). 

#### How a test can be wrong: 

- **False Positive**

    Now we move on to the orange cell labeled false positive. The first of two ways a COVID-19 test can be wrong is when the test predicts positive (saying that the tester has COVID-19) when in fact the tester is negative (tester actually does not have COVID-19). The test is wrong here since it incorrectly predicted that the person had COVID-19 when in fact they did not. This is known as a False Positive (FP).

- **False Negative**

    The lesser mentioned sibling of a False Positive is a False Negative. This would be when the test predicts negative (saying the tester does not have COVID-19), when in fact the tester is positive (tester actually has COVID-19). The test is wrong here it predicted the tester did not have COVID-19 when in fact they did. This is known as a False Negative (FN). 


As an aside, I find people get confused because they relate the word ‘Positive’ to a correct test. I want to clarify for readers that the word ‘Positive’ is related to the prediction of the test. So when understanding these terms, the second word ('Positive'/'Negative') is not referring to whether the test is right or wrong but rather whether the test predicted positive or negative.


### But isn't being right or wrong enough?
Now having read all this, you might wonder isn’t a test simply being right or wrong enough? For example, why does the article referenced at the beginning not simply have a title like this: 

>Wrong tests in Makkovik was ‘huge sigh of relief’ but shows how quickly COVID-19 can take hold

instead of using the words false positive like this:

>False positive in Makkovik was ‘huge sigh of relief’ but shows how quickly COVID-19 can take hold

The reason for this is that how a test is wrong is actually very important and can have very different impacts. For example, in the case of COVID-19, a disease with a high fatality rate and is highly transmissive, it would be much more harmful for a test to be a False Negative compared to a False Positive. 

The impact or consequence of a false positive in this case would be that an individual would have to quarantine themselves and take extra care of themselves. Their way of living may be inconvenienced for a bit in the short term but no one else would really be affected. 

Contrast this to a false negative which would mean that an individual would continue to carry on with their life as they usually do. This might mean physically going into the office to work, going to the supermarket to buy groceries and in general interacting with other people. Because of this test being a false negative, this person could be exposing a lot of other people to COVID-19! The negative impact of a false negative in this context is much worse than that of a false positive. 

Now it should be noted that just because a false negative is worse in this COVID-19 testing scenario it does not mean that false negatives are worse than positives in all situations. Whether one is worse than the other really depends on what the researcher or what the person is after. I would encourage you to think of an example where a false positive might be better than a false negative. If you really can't come up with one, you may be able to find an example in this [article](https://towardsdatascience.com/false-positive-and-false-negative-b29df2c60aca).  

Hopefully, this brief blog post has helped you understand the concepts of false positive and false negative and illustrate its impacts.

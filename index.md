---
layout: page
title: "BeerAdvocate vs RateBeer" 
subtitle: "Which Platform is Best Suited for You?"
cover-img: /assets/img/RB_vs_BA.png
thumbnail-img: /assets/img/RB_vs_BA.png
share-img: /assets/img/RB_vs_BA.png
use-site-title: true
---

# Introduction
It's not uncommon to have to choose between two similar items, whether it's between two books in a bookshop, two different telephones or even between two restaurants on Google. In these situations, we're very happy to find in-store advisers or online reviews (maybe both for the more methodical) to help us make the final choice. But it's much less common to seek advice on choosing between two rating platforms or application on the internet. Perhaps you could ask friends who use them, but if you're not so lucky or if you just want to check what they say, we're offering to be that friend today! Our aim is to help you decide between the two rating platforms: BeerAdvocate and RateBeer, so you can decide which one suits you best. 

To do this, we're going to present several interesting aspects of each of the two platforms, so that you can compare them and get a better idea of how they work, their respective communities and the type of reviews you might find.

# Plateforms description

Today's dilemma is between RateBeer and BeerAdvocate, two competing platforms, and you're here to make a choice. To give you an initial idea, here are some overall figures on these two rivals (obtained from data collected up to July 2017).

# How ratings works ?

What is it? Aren't the ratings calculated in the same way on the 2 sites? I have the impression that 3.5/5 on BeerAdvocate doesn't have the same value as 3.5/5 on Rate Beer ... I need to check this...
After some research, I've found out how the scores are calculated! Great stuff! Users rate beers on 5 topics: appearance, aroma, palate, taste and overall, but the 2 sites don't give the same importance to these topics! As a good statistician, I prefer to check this with my data. The results of my linear regression are the same as on the site, which makes sense. Here are my results: 

{% include_relative figs/rating_coeff.html %}

I'm not happy that the coefficients are different... Does it really matter? Can I be sure that the coefficients are really different? A good old-fashioned statistical test will tell me!  


# Who are the interesting users ?

Next, we turn our attention to the users, the heart of any review platform. Not all reviewers are equal, and some can be considered experts. But what makes an expert? By identifying patterns in user behavior, we aim to determine which users contribute reviews that are more detailed, consistent, and insightful. These "experts" are essential for understanding which platform fosters a community of knowledgeable reviewers.

# What language do they speak ?

With the experts identified, we delve into their reviews to reveal the story they tell about each platform. We analyze their language to understand the regional and linguistic diversity of each platform’s community. This helps us answer questions like: Which platform has a more global reach? Is there a dominant language of discussion on one platform over the other?

# Which sentiment do they express the most?

Let’s be honest, when you’re choosing a platform, it’s not just about the features or how many users it has. It’s also about the vibe. Are the reviews upbeat and encouraging? Or are they super critical and serious? The tone of a platform’s reviews can say a lot about its community and what kind of experience you’ll have there.

To get a feel for the mood on BeerAdvocate and RateBeer, we decided to dive into the reviews of the experts and do a little detective work. Using something called sentiment analysis (basically, a fancy way of figuring out if people are being positive, negative, or neutral), we analyzed the expert's reviews to uncover the overall tone.

This way, we’re not just guessing—we’ve got data to back it up! Is BeerAdvocate full of passionate beer lovers who rave about every sip? Are RateBeer users more critical and straight to the point? Or is it a mix of everything?

Whether you’re looking for a platform with happy vibes or a community that isn’t afraid to tell it like it is, this analysis might help you decide where you’ll feel most at home. Let’s see the way the experts express their taste for a beer !

# What kind of words do they use?

Finally, we assess the richness of the language used in expert reviews. A well-crafted review often reflects the reviewer’s depth of knowledge and expertise. By examining the vocabulary used, we can gauge which platform fosters a more cultivated and constructive reviewing environment, helping users decide where to find reviews they can trust.

# The final choice

Together, these analyses form a comprehensive picture of what each platform offers, allowing beer enthusiasts to make informed decisions about which platform best suits their needs. Whether you value detailed evaluations, insightful reviewers, or a vibrant and diverse community, this project aims to guide you to the right choice.

# References

To complete this project, we have used various resources, which are listed here.

- [[paper][A]] Julian McAuley, Jure Leskovec, Dan Jurafsky, **Learning Attitudes and Attributes from Multi-Aspect Reviews**, Stanford.

- [[paper][B]] Gael Lederrey, Robert West, **When Sheep Shop: Measuring Herding Effects in Product Ratings with Natural Experiments**, EPFL.



- [[website][14]] Wikipedia **Timeline of Computer Animation**

- [[image][G]] By Athanasius Kircher, Public Domain

[A]: http://i.stanford.edu/~julian/pdfs/icdm2012.pdf
[B]: https://dlab.epfl.ch/people/west/pub/Lederrey-West_WWW-18.pdf

[14]: https://en.wikipedia.org/wiki/Timeline_of_computer_animation_in_film_and_television
[G]: https://commons.wikimedia.org/w/index.php?curid=52666213

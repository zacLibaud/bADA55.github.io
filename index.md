---
layout: page
title: "BeerAdvocate vs RateBeer" 
subtitle: "Which Platform is Best Suited for You?"
---

# Introduction
It's not uncommon to have to choose between two similar items, whether it's between two books in a bookshop, two different telephones or even between two restaurants on Google. In these situations, we're very happy to find in-store advisers or online reviews (maybe both for the more methodical) to help us make the final choice. But it's much less common to seek advice on choosing between two rating platforms or application on the internet. Perhaps you could ask friends who use them, but if you're not so lucky or if you just want to check what they say, we're offering to be that friend today! Our aim is to help you decide between the two rating platforms: BeerAdvocate and RateBeer, so you can decide which one suits you best. 

To do this, we're going to present several interesting aspects of each of the two platforms, so that you can compare them and get a better idea of how they work, their respective communities and the type of reviews you might find.

# How ratings works ?

What is it? Aren't the ratings calculated in the same way on the 2 sites? I have the impression that 3.5/5 on BeerAdvocate doesn't have the same value as 3.5/5 on Rate Beer ... I need to check this...
After some research, I've found out how the scores are calculated! Great stuff! Users rate beers on 5 topics: appearance, aroma, palate, taste and overall, but the 2 sites don't give the same importance to these topics! As a good statistician, I prefer to check this with my data. The results of my linear regression are the same as on the site, which makes sense. Here are my results: 

{% include_relative figs/rating_coeff.html %}

I'm not happy that the coefficients are different... Does it really matter? Can I be sure that the coefficients are really different? A good old-fashioned statistical test will tell me!  


# Who are the experts ?

{% include_relative figs/figure_interactive.html %}

# What language do they speak ?

# Which opinion do they express the most?

# What kind of words do they use?

# The final choice

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

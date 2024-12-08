---
layout: page
title: Which Platform is Best Suited for You?
---

# Introduction

Hit musical numbers from the blockbuster movies ‘Dilwale Dulhania Le Jayenge’ and ‘Titanic’ 
continue to occupy a special place in people’s hearts even today. This might make you think: 
What are the secret ingredients of music that enrapture all of us and how does it add magic 
to the movies? With this thought in mind, we will use the CMU Movie Summary Corpus and our 
Spotify Dataset to find out the dominant music attributes (danceability, energy, liveness, etc.) 
in different countries across the world so as to possibly reveal country-specific music styles for 
the top 3 countries (in our combined movie and music dataset). Subsequently, we will observe the change 
in music features and their interplay with the changes in the emotions portrayed by movies in the top 2 
countries (in our combined movie, music and emotion dataset) across the years. Finally, we will connect 
all the dots to reveal how music moves movies towards success. Let's dive deep into the world of music and movies!

# Difference in Notation 

What is it? Aren't the ratings calculated in the same way on the 2 sites? I have the impression that 3.5/5 on BeerAdvocate doesn't have the same value as 3.5/5 on Rate Beer ... I need to check this...
After some research, I've found out how the scores are calculated! Great stuff! Users rate beers on 5 topics: appearance, aroma, palate, taste and overall, but the 2 sites don't give the same importance to these topics! As a good statistician, I prefer to check this with my data. The results of my linear regression are the same as on the site, which makes sense. Here are my results: 

{% include_relative figs/rating_coeff.html %}

I'm not happy that the coefficients are different... Does it really matter? Can I be sure that the coefficients are really different? A good old-fashioned statistical test will tell me!  


# Deciphering Country-Specific Music Styles

{% include_relative figs/figure_interactive.html %}

## Movie Metadata Dataset (CMU Movie Summary Corpus) 

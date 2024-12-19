# Which Platform is Best Suited for You?

This is the repository of the <a href="https://zaclibaud.github.io/bADA55.github.io/" target="_blank" rel="noopener noreferrer">website</a> for the <a href="https://edu.epfl.ch/coursebook/fr/applied-data-analysis-CS-401" target="_blank" rel="noopener noreferrer">CS-401 Applied Data Analysis</a> EPFL course project of the team bADA55.

The repository of the project can be found <a href="https://github.com/epfl-ada/ada-2024-project-bada55" target="_blank" rel="noopener noreferrer">here</a>.


## Abstract
In a world where decisions are increasingly influenced by online platforms, choosing one beer review platform between BeerAdvocate or RateBeer, can feel like choosing between Spotify and Deezer. Just as music lovers want to know which streaming service better matches their taste, beer enthusiasts want to understand which platform offers more reliable and insightful reviews. Our goal is to help answer this question by diving deep into the unique characteristics of both platforms to compare them.

## Research questions and according methods

### How does the rating work on both platform ?
The same overall rating on BeerAdvocate and RateBeer does not reflect identical scores across different topics. In theory, if a user provides the same scores and descriptions for a beer on both platforms, the overall score would still differ between the two sites.

**Method:** For this we will use a linear regression model to find the coefficient for each parameter (aroma, taste, palate, appearance, overall).

### Who are the interesting/experts users ?

Not all reviewers are equal, and some can be considered experts. But what makes an expert? By identifying patterns in user behavior, we aim to determine which users contribute reviews that are more detailed, consistent, and insightful. These “experts” are essential for understanding which platform fosters a community of knowledgeable reviewers.

**Method:** For this, our goal is to use k-means clustering with features like total reviews, mean time and standard deviation spacing, and rating std to see if we can extract a group of “experts” users.

### What language do they speak ?

Before going into the analysis of the reviews of the experts users we identify their languages using fasttext.

### Which sentiment do they express the most ?

Using SentimentIntensityAnalyzer from Vader we aim to see the sentiment scores and the overall sentiment of each review.

### What kind of words to they use ?

Identify the topics of experts reviews using LDA.

## Distribution of tasks

- François GOYBET : linear regression for ratings, creating .py files, kmeans
- Zacharie LIBAUD : preprocessing, language analysis, website
- Zoé MONNARD : language detection, sentimental analysis, website
- William SCHMID : kmean clustering
- Pierre TESSIER : website




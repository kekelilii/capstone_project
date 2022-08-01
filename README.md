# Capstone Project

We are working for a major entertainment corporation that is trying to get a better handle on both what makes a good movie as well as a better understanding of the viewers. We need to do prediction, tests, and analysis to help make decisions. This is a final project of Introduction to Data Science by professor William Pascal(NYU). The project covers most of the content throughout the class, including dimentional reduction(PCA), clustering, correlation, hypothesis test, regression, etc. The structure of the project is basicly answering questions listed below. Answers and proofs are documented in [Capstone_KellyDeng.pdf](Capstone_KellyDeng.pdf). Python is the only language used. 

## Dataset Description
This dataset features ratings data of 400 movies from 1097 research participants and is contained in the file [movieReplicationSet.csv](movieReplicationSet.csv). It is organized as follows:
- 1st row: Headers (Movie titles/questions) – note that the indexing in this list is from 1
- Row 2-1098: Responses from individual participants
- Columns 1-400: These columns contain the ratings for the 400 movies (0 to 4, and missing) Columns 401-420: These columns contain self-assessments on sensation seeking behaviors (1-5) Columns 421-464: These columns contain responses to personality questions (1-5)
- Columns 465-474: These columns contain self-reported movie experience ratings (1-5)
- Column 475: Gender identity (1 = female, 2 = male, 3 = self-described)
- Column 476: Only child (1 = yes, 0 = no, -1 = no response)
- Column 477: Social viewing preference – “movies are best enjoyed alone” (1 = y, 0 = n, -1 = nr)

## Questions
1) What is the relationship between sensation seeking and movie experience?
2) Is there evidence of personality types based on the data of these research participants? If so,
characterize these types both quantitatively and narratively.
3) Are movies that are more popular rated higher than movies that are less popular?
4) Is enjoyment of ‘Shrek (2001)’ gendered, i.e. do male and female viewers rate it differently?
5) Do people who are only children enjoy ‘The Lion King (1994)’ more than people with siblings?
6) Do people who like to watch movies socially enjoy ‘The Wolf of Wall Street (2013)’ more than
those who prefer to watch them alone?
7) There are ratings on movies from several franchises ([‘Star Wars’, ‘Harry Potter’, ‘The Matrix’,
‘Indiana Jones’, ‘Jurassic Park’, ‘Pirates of the Caribbean’, ‘Toy Story’, ‘Batman’]) in this
dataset. How many of these are of inconsistent quality, as experienced by viewers?
8) Build a prediction model of your choice (regression or supervised learning) to predict movie
ratings (for all 400 movies) from personality factors only. Make sure to use cross-validation
methods to avoid overfitting and characterize the accuracy of your model.
9) Build a prediction model of your choice (regression or supervised learning) to predict movie
ratings (for all 400 movies) from gender identity, sibship status and social viewing preferences (columns 475-477) only. Make sure to use cross-validation methods to avoid overfitting and characterize the accuracy of your model.
10) Build a prediction model of your choice (regression or supervised learning) to predict movie ratings (for all 400 movies) from all available factors that are not movie ratings (columns 401- 477). Make sure to use cross-validation methods to avoid overfitting and characterize the accuracy of your model.

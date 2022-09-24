# 13-3. An analysis of the subscription-based book-reading service's database

## Status
Complete

## Task

Using SQL in this project, I analyzed the database of a large service that provides subscription-based books. This database contains information about books, publishers, authors, as well as user reviews. Analysis of this data will help formulate a new value proposition.

When formulating a new value proposition, I recommend using the following information from the database:

In the reviews_cnt table there are the titles of the most popular books, the number of reviews, and the average rating of each of the books. In the publishers_50 table, there are publishers that have released books over 50 pages. In the ratings_max table, there are authors with the highest average book rating. Consider these tables when drafting startup proposals. Only books with 50 or more ratings were taken into account. In addition, it was calculated that the average number of reviews from users who have given more than 50 ratings is 24.3. As a result, we were able to make more accurate ratings.

## Tools and python libraries

*PostgreSQL*, *sqlalchemy*, *pandas*

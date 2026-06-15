# Hacker News Trend Analysis using SQL

## Project Overview

This project analyzes data from Hacker News, a popular technology-focused community platform. The dataset contains information about stories, users, scores, timestamps, and URLs.

The objective of this project is to identify user engagement patterns, content source trends, and optimal posting times using SQL.

## Dataset

The dataset contains the following fields:

- title
- user
- score
- timestamp
- url

## Objectives

- Identify the highest-scoring stories
- Analyze score distribution among users
- Detect repeated spam/Rickroll links
- Compare popular content sources
- Determine the best time to post stories

## SQL Skills Demonstrated

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- Aggregate Functions
  - COUNT()
  - SUM()
  - AVG()
- CASE Statements
- Date & Time Functions
  - STRFTIME()
- Data Aggregation

## Key Findings

### User Contribution Analysis
A small percentage of users contributed a significant portion of the overall platform score, supporting the 1-9-90 participation rule commonly observed in online communities.

### Content Source Analysis
GitHub, Medium, and New York Times were among the most frequently shared content sources.

### Spam Link Detection
Several users repeatedly posted the same YouTube Rickroll link.

### Posting Time Analysis
Story engagement varied throughout the day, with certain hours producing higher average scores.

## Project Files

- hacker_news_queries.sql
- findings.md

## Project Source

Completed as part of the Codecademy SQL learning path.
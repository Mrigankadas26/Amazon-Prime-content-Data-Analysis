# Amazon-Prime-content-Data-Analysis
# Amazon Prime Content Intelligence Analysis Using SQL

## Overview

This project presents an analytical exploration of Amazon Prime’s movies and TV shows dataset using SQL. The objective of the project was to move beyond basic streaming platform analysis and build a more insight-driven analysis focused on ratings, genres, runtime behavior, production trends, and actor-director analytics.

The project combines structured SQL analysis and relational querying to identify meaningful patterns within Amazon Prime’s content library.

---

## Objectives

* Analyze Amazon Prime’s content distribution across movies and TV shows
* Identify highly rated genres and content categories
* Study runtime patterns and their relationship with audience ratings
* Explore production trends across years and countries
* Analyze actor and director participation using relational data
* Generate analytical insights using advanced SQL concepts

---

## Dataset

The project uses two datasets:

### 1. Amazon_titles

Contains:

* Title information
* Type (Movie/Show)
* Genres
* Runtime
* Release year
* IMDB/TMDB ratings
* Popularity metrics
* Production countries

### 2. Amazon_credits

Contains:

* Actor names
* Director names
* Roles
* Character information
* Title IDs

The two datasets were connected using the common `id` field to enable relational analysis.

---

## Tools & Technologies

* SQL
* MySQL
* Data Cleaning & Transformation
* Window Functions
* Joins & Subqueries

---

## SQL Analysis Performed

### Content Analysis

* Total movies and TV shows
* Content growth over time
* Decade-wise distribution

### Rating Intelligence

* Top-rated movies and shows
* Highest rated genres
* Content quality segmentation
* Popularity vs rating analysis

### Runtime Analysis

* Runtime category segmentation
* Runtime vs audience rating comparison

### Genre Intelligence

* Most dominant genres
* Genre performance analysis
* Genre popularity comparison

### Relational Analytics

* Most featured actors
* Highest rated actors
* Directors with most highly rated content
* Actor-director collaboration insights
* Genre diversity of actors

---

## Key Insights

* Long-duration movies showed moderately higher audience ratings compared to medium-length content.
* Drama and documentary-heavy genres consistently performed better in terms of audience ratings.
* Content production increased significantly after the 2000s, indicating rapid streaming catalog expansion.
* Certain actors and directors appeared consistently in highly rated productions, suggesting strong audience engagement patterns.
* Genre popularity did not always correlate with higher audience ratings, revealing differences between reach and perceived quality.

---

## Project Highlights

* Used advanced SQL concepts including:

  * Window Functions
  * Dense Ranking
  * Conditional Aggregation
  * Joins
  * Subqueries
* Focused on analytical storytelling instead of only descriptive statistics
* Built relational insights using both titles and credits datasets
* Designed the project to simulate real-world streaming platform analytics

---

## Conclusion

This project demonstrates how SQL can be used to transform raw entertainment datasets into meaningful analytical insights. The analysis highlights patterns in audience preferences, content strategy, genre performance, and creator participation within Amazon Prime’s streaming catalog.

The project also helped strengthen practical skills in SQL analytics, relational data modeling, and insight generation using real-world datasets.

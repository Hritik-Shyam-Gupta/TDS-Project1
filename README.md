# IITM BS - Tool in Data Science (TDS) Project - 1
## GitHub Users in Paris:200

This repository contains data about GitHub users in Paris, with over 200 followers along with up to 500 recently pushed repositories per user from Paris.

## An explanation of how data is scrapped: Scrapping Mechanism

The Data is scrapped using GitHub restful API with a personal Developer access token. The scrapping logic and code is present in the below mentioned file:

### _Scraping mechanism_ <a href="">(Code)</a>

### Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-31
- Only included users with 200+ followers
- Up to 500 most recently pushed repositories per user

### Files Description

1. `users.csv`: Contains information about 385 GitHub users in Paris with over 200 followers
2. `repositories.csv`: Contains information about 37659 public repositories from these users
3. `TDS_Project_1_Analysis`: Contains the findings and Analysis of the above repositories as part of the questionnaire of TDS Project - 1
4. `TDS Project 1 - Scrapping File`: Code logic file for scrapping user and repository data from GitHub using GitHub Restful API

## 2. Some facts discovered from the analysis: Interesting Insight
- Found that developers associated with educational institutions are among the most popular in Paris’s GitHub community.
- Contributing to popular open-source repositories and being associated with an educational institution may help increase followers and visibility.
- Most of the contributions were in Javascript, Python, and HTML, in this order.
- The second most popular programming language among users who joined after 2020 is Python with 68 repositories.
- The programming language with the highest average number of stars per repository is Blade with an average of 1632.00 stars.
- The majority of developers work at HUGGINGFACE with 8 developers.

## 3. An actionable recommendation for developers based on your analysis:

- Language with the most README word count and Images: JavaScript and Python (in order)
- Most of the repositories that have images in the README file have a good number of followers and forks, along with a good rating. A well-crafted README file helps users understand the purpose of the Repository at a glance and attracts users to follow for further contributions
- JavaScript & Python are still really popular languages to work. Aspiring developers should stick to these and refine their skills around these languages

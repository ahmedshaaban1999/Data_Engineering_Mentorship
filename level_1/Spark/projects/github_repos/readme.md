# Github Most Popular repos
## Project Overview:
You were given a group of json files that has data for the top starred repos on github according to different search terms. We need to extract some information from the json files and load it into a sql database using Apache Spark. You are free to use any Apache Spark API and any sql database.


## Resources:
archive file containing 30 json files. [source](https://www.kaggle.com/datasets/anshulmehtakaggl/top-1000-github-repositories-for-multiple-domains?select=Spark.json)

## Requirements:
1. Create a table for programming languages called "programming_lang" which has two columns, the programming language name and the number of repos using it.
2. Create a table for the organization-type accounts called "organizations_stars" which has two columns, the organization name and the total number of stars across all of its repos in all the files.
3. Create a table for the search terms called "search_terms_relevance" which has two columns, the search term - a.k.a. the file name - and the relevance score for all the repos for this search term. We use a self-defined formular for calculating the relevance where relevance score = 1.5 * forks + 1.32 * subscribers + 1.04 * stars.

## Key Deliverables:
-	Apache Spark code.

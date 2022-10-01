# IMDB Analysis
- Juliana Sahagun
- August 2022
 ## Business Problem:
- Analyze what makes a movie successful and provide recommendations to the stakeholder on how to make a successful movie

#### Data: Original Source

  - [Data Dictionary](https://www.imdb.com/interfaces/)
  - [Downloads page](https://datasets.imdbws.com/)
  - Files used
    - title.basics.tsv.gz
    - title.ratings.tsv.gz
    - title.akas.tsv.gz
#### Specifications
1. Excluded any movie with missing values for genre or runtime
2. Included only full-length movies (titleType = "movie").
3. Included only fictional movies (not from documentary genre)
4. Included only movies that were released 2000 - 2021 (include 2000 and 2021)
5. Included only movies that were released in the United States
#### Methods:
- Clean and filtered data to meet the specidicatons above.
- Used an API to extract box office revenue and profit data to add to your IMDB data and perform exploratory data analysis.
- Construct and export a MySQL database using combined data ('imdb_id','budget','revenue', 'certification')
#### Results/ Recommendations:
The genre of a movie doesnt affect how much a revenue a movie genrates. Movies with higher budgets haf a higher revuenue. I would recommend 
## For Further Information:
For any additional questions or concerns in regards to my project, please contact me at julianas4013@gmail.com. Thank you!

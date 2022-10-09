# IMDB Analysis
- Juliana Sahagun
- August 2022
 ## Business Problem:
Analyze what makes a movie successful and provide recommendations to the stakeholder on how to make a successful movie

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
- Clean and filtered data to meet the specifications above.
 - Used an API to extract box office revenue and profit data to add to your IMDB data and perform exploratory data analysis.
 - Construct and export a MySQL database using combined data ('imdb_id','budget','revenue', 'certification')
#### Visualizations:
###### Visual 1: Overall, rated-R had the highest count in movies while G rated movies had the lowest.
![image](https://user-images.githubusercontent.com/104885846/193429779-1a54fdeb-a65a-4701-8901-b1f48cbb6e5e.png)
###### Visual 2: Demonstrates that PG-13, PG and G rated movies had the highest budget
![image](https://user-images.githubusercontent.com/104885846/193429754-0f70ce74-c59f-49de-871e-27a341d4ffc6.png)
###### Visual 3: Shows that the same movies with the highest budget, also had the highest revenue
![image](https://user-images.githubusercontent.com/104885846/193429770-4328e4d5-a9da-427a-9718-5237a946e636.png)

#### Results/ Recommendations:
...
## For Further Information:
For any additional questions or concerns in regards to my project, please contact me at julianas4013@gmail.com. Thank you!

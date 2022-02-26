# Movies-ETL
Module 8

## Write an ETL Function to Read Three Data Files

The goal of this deliverable is to write a function that reads in the three data files and creates three separate DataFrames.

Wiki movies
[https://github.com/cbello03061/Movies-ETL/blob/main/Image1.png]

Kaggle metadata
[https://github.com/cbello03061/Movies-ETL/blob/main/image%202.png]

Raitings
[https://github.com/cbello03061/Movies-ETL/blob/main/image%203.png]

## Extract and Transform the Wikipedia Data

Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.

Wiki movies
[https://github.com/cbello03061/Movies-ETL/blob/main/image%204.png]

Wiki movies DataFrame to a list
[https://github.com/cbello03061/Movies-ETL/blob/main/image%205.png]

## Extract and Transform the Kaggle data

With us knologe, code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

[https://github.com/cbello03061/Movies-ETL/blob/main/image%206.png]

[https://github.com/cbello03061/Movies-ETL/blob/main/image%207.png]

## Create the Movie Database

Using  our knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database. We have to determinate the count of movies and reitings

Movies
[https://github.com/cbello03061/Movies-ETL/blob/main/challenge/Resources/movies_query.png]

Raitings

[https://github.com/cbello03061/Movies-ETL/blob/main/challenge/Resources/ratings_query.png]

## Movies_metadata

Within the files of the deliveries, movies_metadata must be uploaded to Hit Hub, but it exceeds the limit of megabytes that the tool allows uploading, that is why, through the OneDrive tool, I provide the link so that they can verify the manipulation of the file .

link [https://1drv.ms/u/s!BMSlgfm90ilJhfNQp14tnQFcemIWsg?e=gMyFiH]
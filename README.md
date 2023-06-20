# EDA-on-Netflix-Dataset

![netflix-tv-interface](https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/e305d31b-a49d-4c18-a4f9-19605a724d73)


## Aim

This is an Exploratory Data Analysis project on Netflix dataset using Python. The goal is to analyse and extract meaningful insights from the dataset . A dashboard has also been created by the help of tableau to make the analysis interactive.



## Dataset from [kaggle](https://www.kaggle.com/code/mysarahmadbhat/eda-on-netflix/notebook)

This dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, description, date added on netflix, genre, country, type and title.



## Tools Used
* Python Library- **Pandas, NumPy, Seaborn, Matplotlib**
* **Tableau**



## Methodology

* Data Cleaning
* EDA & Data Visualization
* Insights
 
## Data Cleaning

### Step 1

<img width="725" alt="a3" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/4693a60d-b875-4c04-b308-fda5108457e0">

**Most of the values are missing from Director Column and some from Cast and Country columm and very few from date, rating and duration column**

### Step 2

<img width="690" alt="a4" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/2f0f61f4-c242-4e14-8d62-702fac35adae">

### Step 3

<img width="773" alt="a5" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/bdaeb74f-cdf9-4f89-9254-b28ded2d70a6">

**There are no duplicate values**



## EDA & Data Visualization

### 1. Distribution of content

<img width="248" alt="content" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/af1574fb-71c7-4be1-9723-3536c4294b3e">

**So there are more movies than tv shows. 70% content is Movies and 30% Content is Tv-shows.**



### 2. Top 10 Countries by Movies and Tv Shows

<img width="641" alt="countries_by_movies_and_shows" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/58b0a8f1-184c-4e60-82c4-c38a88ec268b">

**Therefore most of the movies and shows are from united states, followed by India and then United Kingdom**



### 3. Top 10 Countries by Movies

**Let's check which country gives the maximum no of movies**

<img width="653" alt="countries_by_movies" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/5a1ce5a3-60e8-4439-ab04-50787b8402aa">

**The country with maximum movies is again united states followed by India and then United Kingdom**



### 4. Top 10 Countries by Tv Shows

**Let's check which country gives the maximum no of Tv shows**

<img width="649" alt="countries_by_tv_shows" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/8029a08e-17c0-4996-8bb9-51eb271a7c7b">

**The country with maximum tv shows is again united states followed by united kingdom and then japan. Here India is at 5th position. In movies it was at 2nd position.**



### 5. Rating 

<img width="587" alt="Rating" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/3a235ede-333a-4760-8ec4-04d7fe2cd1b0">

**We can see that TV-MA rating is highest. It means that most of the tv shows are for adults (18+)**



### 6. Top 10 Directors

**We can have a look at the top 10 directors**

<img width="698" alt="Top_10_directors" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/dc95966c-6322-4add-9979-428f40154335">



### 7. Duration of movies

<img width="608" alt="Duration_of_movies" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/65567791-640b-47a1-a8fe-aec77ac49d2a">

**Therefore duration of most of the movies lies in the range of 90 to 100 minutes**



### 8. Duration of Tv Shows

<img width="617" alt="Duration_of_tv_shows" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/ff2585bb-af5c-4ca5-a6cc-8d90cb8f38d5">

**We can conclude that maximum Tv shows have only season 1.**



### 9. Top 10 Movies and Tv shows by date added on netflix

<img width="571" alt="date_added" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/737c7d05-5723-4090-81bc-424e64a10fdf">

**So we can see that most of the movies and tv shows were added in 2019 Then it decreases may be because of Corona**


### 10. Distribution of content by date added on netflix




<img width="520" alt="a10" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/c3442fdb-46af-42a3-97b3-4a62847f9138">



### 11. Top 10 Genre

<img width="761" alt="Top_10_genre" src="https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/d300a475-2c41-43af-beb1-889deaa9d2b6">

**Dramas, International movies genre is the highest followed by Documentaries.**



## To make the analysis visually interactive, I have also created a dashboard using tableau

### Key metrics displayed in the dashboard include-

* Cast, Genre, Description, Director, Release Year, Rating and Duration
* Distribution of content
* Movies and Tv shows by country
* Top 10 Ratings
* Top 10 Genre
* Type over the year

### The dashboard allows filtering by type( wheather it is a movie or a tv show) and title.

Here we can see the [Interactive dashboard](https://public.tableau.com/app/profile/tableau7010)

![Dashboard 1 (1)](https://github.com/ishita9988/EDA-on-Netflix-Dataset/assets/129153274/ea882217-123d-4e98-9dff-f28d9479d187)



## Insights

* There are some missing values in director, cast and country column.
* United States has the most number of tv shows and movies followed by india and united kingdom
* There are more movies than tv shows. 70% content is Movies and 30% Content is Tv-shows.
* Most of the movies and tv shows are for adults (18+)
* Year 2018 marked the highest number of movies and tv shows release.Then it decreased may be because of Corona:
* Duration of most movies are in the range of 90 to 100 minutes
* Dramas,international movies is the most prefered genre followed by Documentaries.
* Majority of the directors made single Movie or TV Show on Netflix.

 

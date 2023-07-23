# Phase 1 Project

#### Author: Mwenda Mugambi

## Project Overview
For this project, I used exploratory data analysis on datasets from the below websites to generate insights for Microsoft.
* https://www.boxofficemojo.com/
* https://www.imdb.com/
* https://www.rottentomatoes.com/
* https://www.themoviedb.org/
* https://www.the-numbers.com/

## Business Problem
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. I am charged with exploring what types of films are currently doing the best at the box office. I will then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## The Data Used
For this project, I used exploratory data analysis on these datasets:
* 1. Bom_movies
* 2. title_basics 
* 3. title_akas 
* 4. name_basics 
* 5. movie_budgets 
* 6. title_crew 

## Data Cleaning and Analysis
I did a deep dive into the datasets to understand the structure and state of the data.

After understanding the data and the state it was in, I started to clean it up. Cleaning was essential so that we can have accurate data to work with when we do a deeper analysis and get to answer some questions at the end of our analysis.

I used the pandas, seaborn and matplotlib libraries, and python to do the exploratory data analysis, visualize the datasets and answer some questions. 

## Merging DataFrames to do deeper analysis
After reviewing the data, I got an idea of the questions I could answer by merging the data Frames.

### Questions
1. Which studios have the Highiest ROI and make the most profitable Movies?
2. Which genres are popular among the studios?
3. Which genres are profitable and have the highest ROI?
4. Which Directors have the most profitable movies?
5. What are the number of movies produced over the years?

## Results
http://localhost:8888/view/Graphs/2.jpg
* UTV, WB(NL), ParV and FD, Had movies with the highest ROI.
* P/DW and BV had the most profitable movies.

http://localhost:8888/view/Graphs/1.jpg
* Drama, Comedy, Action, Crime and Thriller genres are the most popular genres produced.

http://localhost:8888/view/Graphs/3.jpg
* Action, Adventure, Sci-Fi, Thriller and Crime genres were the most profitable.

http://localhost:8888/view/Graphs/4.jpg
* Horror, Mystery and Thriller  genres have the highest ROI.

http://localhost:8888/view/Graphs/5.jpg
* James Wan, Michael Bay and Christopher Nolan have the most profitable movies.

http://localhost:8888/view/Graphs/6.jpg
* 2017 had the highest number of movie releases.
* There was a drastic drop in the number of movie releases from 2018 to 2020.

## Conclusion
* Like many other businesses, there Covid 19 Pandemic affected the entertainmaint industrie and movie production companies.
* The "Action" and "Thriller" genres are quite popular among the studios. Even though they are among the genres with the highest production budgets, they are also among the genres that are most profitable.
* "Adventure", and "sci-Fi" also tend to make high profits even though they also have high production budgets.
* "Horror", "Mystrey" and "Comedy" genres offer the highest ROI- This could be attributed to the lower production budgets.
* "Thriller" genre however seems to be a winner as even with the high production budgets, the genre tends to have high profits and ROI.
* "WB", "UTV", "Uni", "Grtindia" and "Par" studios seem to be successful as they trend to make profits and have high ROI on their movie productions.
* Most profitable studios are P/DW(Pixar and DreamWorks) and BV(Buena Vista)a distribution brand and subsidiary of The Walt Disney Studios, which after further research discovered the primary genres are "animations" 

## Recommendations.

#### 1. Winning Genres:
Microsoft Should work to develop more movies in "Action", "Thriller", "Adventure" and "Sci-Fi" genres or a blend of the genres as they tend to have been the most profitable over the years.

#### 2. Budget allocation
Microsoft should allocate higher production budgets to the "Action", "Sci-Fi", "Thriller" and  "Adventure" genres to maximize on the production quality as they have the the most profitable genres over the years.
Lower budgets to be allocated to the "Horror" and "Mystery" genres. Even though the have the highest ROI, they tend to have a niche audience.

#### 3.  Opportunities to tap into
With Walt Disney, Pixar and Dreamworks being the most profitable studios, Their primary genre production is "Animations" 
There lies an oppurtunity for Microsoft to tap into the success of the genre as it tends to have a wide target audience.

#### 4. Directors 
Microsoft already being a successful reputable company, Colaborating with the the directors with the most profitable movies on their respective prefered genres will bring more credibility and buzz around the movies before the release.

#### 5. Market Penetration
With the drastic drop in movie production from 2018, Microsoft should consider diversifying the strategy to include a subscription based Movie streaming platform to satisfy the current consumer behavior preference.

Instead of coming in to compete with the already successful studios in the industry. Having a streaming platform will offer an opportunity to partner with the other studios to have their movies on the platform and could also be exlusive releases for Microsoft Studio movies.

## Next Steps
* Deeper analysis on Walt Disney and Dreamworks strategies should be done on the genre types and quality of the animation movies before getting into the production. 
* Proactive analysis of the industry landscape to mitigate any potential risks or tap into new technologies and opportunities.
* Microsoft should also do research on the already existing movie streaming platforms to understand the landscape. Getting to incorporate machine learning algorithms on the platform would be essensial in order to offer the audience a bespoke experience. This would further go to inform future strategies in movie production as it will be Microsoft's first party data to consumer preferences.
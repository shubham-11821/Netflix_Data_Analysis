# Netflix_Data_Analysis
# Problem Statement
- Data Cleaning
- Missing value detection
- Handling missing values
- Unnesting columns having multiple values in a single column
- Preparing data for detailed analysis

# This notebook shows data analysis covering below in details:-
- Reading data & checking for various metrics.
- Preprocessing of data.
- Detection of missing values and it's handling.
- Cleaning data.
- Handling categorical attributes.
- Statistical Summary such as -> 5 point summary for numerical values -> Oldest movie & tv show -> Longest and Shortest movie and tv show considering duration.
- Types of content on the platform and its contribution.
- Distribution of different types of content as per rating.
- Distribution of different types of content as per release year.
- Year-wise addition of different types of content on the platform.
- Month-wise addition of different types of content on the platform.
- Day-wise addition of different types of content on the platform.
- Number of unique actors, directors, countries, genre & rating.
- Distribution of content genre-wise.
- Top 10 genre for movies and tv shows.
- Top 20 countries with most content, most movies & tv shows.
- Top 20 content, movie & tv shows producing directors.
- Top 20 actors with most content, movies & tv shows.
- Genre-wise distribution of actor and directors content for different types of content.
- Distribution of movies and tv shows across genres with repect to duration.
- Distribution of movies and tv shows across countries with respect to duration.
- Correlation between different attributes for movies and tv shows.
- Correlation between different genres of movies.

# Insights (The insights is based on the data without considering missing values)

- There are two types of content available on the platform (Movies and TV shows)
- There are in total 4991 directors and 36392 actors whose content are available on the platform.
- Content is available s 127 different countries out of which movies are available in 123 countries and Tv shows are available in only 67 countries.
- Content available comprises of 42 genres and 14 different ratings.
- Median duration of movies available on the platform is 98 minutes and TV show is 1 season.
- Platform has contents released between 1925 to 2021 but 50% of the content available were released after 2017.
- There is an uneven distribution in the addition of the content on the platform. Half of the content available on the platform was added in last 3 years.
- Contribution of movies is more than double tv shows on the platform.
- There is an uneven distribution in the number of contents present in different rating categories.
- Addition of content on the platform each month is almost consistent with lowest addition in february.
- For Movies, majority of it has duration of around 100 minutes. For Tv Shows, Majority of them have less than 2 seasons.
- We can see that majority of content was added on the platform after 2015 irrespective of their release year.
- Movies released around 1950's were of shorted duration but movies released later had wide range in terms of duration.
- Majority of TV shows had less than 5 seasons.
- More than 50% of TV shows available on platform has 1 season only.
- Movies contribute to 69.7% of the content on platform and 30.3% are TV shows.
- TV-MA, TV-14, R, PG-13 & TV-PG are the topmost rated category in terms of number of movies available.
- TV-MA, TV-14, TV-PG, TV-Y7 & TV-Y are topmost rated category in terms of number of TV-shows available.
- Majority of the content was released in last 5 years.
- There are more number of movies released compared to TV shows for every year except in 2021.
- There is no significant difference between months in terms of addition of content on the platform.
- July is the month when most number of contents are added and february is when lowest number of contents are added.
- TV Shows added each month is always less compared to Movies.
- We can see that Friday is the most preferred day for content addition on platform and weekend is least preferred.
- We can see International Movies and International TV Shows are the leading Genre for Movies and Tv Show respectively.
- Out of 127 countries in which the content is available, approximately only a quarter of countries are there in which number of content available is greater than 100.
- Out of around 5k directors, only around 100 directors have their 5 or more contents available on the platform.
- Movies and TV shows genres have lowest number of movies and tv shows respectively.
- International Movies, Dramas, Comedies, Documentaries and Action & Adventure are the top 5 genre having the highest number of movies.
- International TV Shows, TV Dramas, TV Comedies, Crime TV Shows and Kids' TV are the top 5 genre having the highest number of tv shows.
- USA, India, UK, Canada and France has the most number of content available on the platform.
- Rajiv Chilaka has directed the most number of movies by a single director.
- Ken Burns and Alastair Fothergill has director most number of TV shows by a single director.
- Anupam Kher has acted in the most number of movies by a single actor.
- Takahiro Sakurai has acted in the most number of tv shows by a single actor.
- Dramas and International movies genres are leading in terms of number of actors having their content in that particular genre for movies.
- International TV Shows genre is leading in terms of number of actors having their content in that particular genre for tv shows.
- International movies genres is leading in terms of number of directors having their content in that particular genre for movies.
- International TV shows genres is leading in terms of number of directors having their content in that particular genre for tv shows.
- For Movies, Classical movies have the highest median duration across genre and Movie genre has the lowest median duration
- We can see that Soviet era movies had hign median duration and Syrian movies has lowest median duration.
- For movies, Classic & Cult Tv have the highest median duration across genre and there are multiple genre in tv shows having only one season.
- For TV shows, Countries producing lower number of TV shows have high median duration and Countries producing more number of TV shows have low median duration.
- For movies, There is significant positive correlation between (cast and director) , (cast and date_added) and (director and date_added). There is negative - correlation between (country and genre) and (rating and country).
- For Tv shows, There is significant positive correlation between (cast and release_year) and (cast and date_added) and there is significant negative correlation between (country and duration) and (cast and genre).
- Following genres are negatively correlated : -> Documentaries and Drama, -> International Tv Shows with Comedies and Dramas
- Following genres are positively correlated : -> Action & adventure with Anime Features and Sci-Fi & Fantasy, -> International Tv Shows and Anime Series, -> TV Comedies with International TV Shows and Kids' TV, -> Horror movies are thrillers, -> TV Mysteries are TV Horrors
- For movies, It's unlikely that Dramas will be documentaries too and International movies will be Children & Family movies. It's very likely that International and Independent movies will be dramas and sports movies will be documentaries.
- For tv shows, It's unlikely that International TV shows will be Kids TV and It's very likely that Science & Nature TV will be Docuseries.

# Business Insights

- Content is available in 127 different countries out of which movies are available in 123 countries and Tv shows are available in only 67 countries. Also, in most of the countries very few number of content is available. It seems platform is not much poplular in many small countries.
- Platform is native to United States so it has the most content availabe in that country.
- Movies are dominating tv shows in terms of amount of content on the platform.
- Rise in number of movies released started from 1980 and it continued to grow significantly till around 2020 and declined later might be due to Covid. As globalization around the world increased, entertainment industry expanded too.
- Rise in number of TV Shows released started from 2000 and it continued to grow significantly till 2020 and declined later might be due to Covid. With increase in availability of TV at homes this number has started increasing.
- Median duration of movies available on the platform is 98 minutes and TV show is 1 season. It seems most of the tv shows have their story line ending in a single season.
- Platform has contents released between 1925 to 2021 but 50% of the content available were released after 2017. Much of contents released in 20th Century are not yet added on the platform.
- USA, India, UK, Canada and France has the most number of content available on the platform. Majority of content are available in developed or developing countries.
- Out of around 5k directors, only around 100 directors have their 5 or more contents available on the platform. Most of the directors are either new to the industry or their content was not much liked.
- For TV shows, Countries producing lower number of TV shows have high median duration and Countries producing more number of TV shows have low median duration. It seems the countries where less number of shows are available they tend to increase the number seasons.
- For movies, There is significant positive correlation between (cast and director) , (cast and date_added) and (director and date_added). There is negative - correlation between (country and genre) and (rating and country). This show that a set directors and cast prefer working together. Also, contents are added on the platform according to cast and directors.
- Most actors and directors prefer working on International movies and International TV shows..
- For Tv shows, There is significant positive correlation between (cast and release_year) and (cast and date_added) and there is significant negative correlation between (country and duration) and (cast and genre). Content on the platform is added based on the cast but it shows that cast are not sticked only to a single genre.
- Friday is the most preferred day for adding the content on the platform as there is high chance of views due to weekend following that day.
- Indian actors are leading in number of contents per actor.

# Recommendations

- Old classical contents should be made available on the platform as there are very few older moviess and TV shows available on the platform. This will attract older generations to use the platform.
- Netflix should come up with marketing ideas to increase the popularity of the platform in under developed nations.
- Platform can liase with directors and cast of the countries where there are very few contents available and provide them necessary help to create more contents.
- Business should work on bring more local content on the platform according to the country.
- They should also plan on increasing the amount of content on genres which has very few contents.
- We can see that directors have a preferred cast for working on their content, business can place itself between the cast and director to create an agreement between them regarding availability and understand their need so that they can work together.
- Business can interact with actors and directors through some support channel to understand and take their feedback and see business can encourage them to bring their content on the platform.
- There are a lot of countries where there are very few content, business can appoint a team to understand the entertainment industry of that particulary country and come up with measure how they can be encouraged to create more content specific to the platform.
- Only few rating categories have very high content on the platform, business should make a plan to bring more content to the platform for those rating where the amount of content is low.
- Content from variety of genres should be brought on the platform. We can see that most of the content are from International Movies and TV shows genre. More content from other popular genres should be added on the platform.

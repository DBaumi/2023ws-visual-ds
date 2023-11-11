# Discover
Name: David Baumgartner  
StudentID: 11721765  

## Describe topic
I chose the proposed topic "How has the market for video games developed in recent years and what impact has the pandemic had on the market?" from the area of the gaming market. This topic is very interesting for me personally. Not only because I also play video games, but I also witnessed changes in how my friends, or in general people, interact with their friends. Different lockdowns forced everyone across the globe to adapt how we spent time with our friends. Some of the people who never (or very rarely) played video games, started to play games just to talk to friends and still feel connected even though personal contact was not possible.  
The pandemic not only changed the behaviour of people to play more video games but also changed the video game market. It created new trends in the gaming market, where some games that existed for years already saw a steady increase in peak player count. For instance, games like Among Us or Minecraft were released on 15. June 2018 and 18. November 2011 respectively. Meaning, the games already existed but saw a big increase in players when the pandemic struck across the globe.  

For me, interesting data sets that could help find key insights for this topic could involve...
 - Game popularity of games: show which games saw a big increase in their player base and what became more popular (changes in game popularity)
 - Game releases: could show which new games were created and what genres or platforms were most played on (player behaviour change)
 - Esports earnings: might give insights into how much sponsors invest in the esports scene (potential investments for big companies)

Both data sets should have dates, that start before the pandemic and continue after it. With this, trends during corona can be seen but also comparisons to before the pandemic can be made. The timespan of the pandemic is declared by the world health organization WHO to have started on January 30th of 2020 and ended on May 5th 2023.  

## Describe data sets
For my data sets I decided to choose them from Kaggle and since the topic is about video games, I checked for data that is gathered from Steam, one of the largest digital distribution platforms, multiplayer game system and social networking site.  

### Steam popularity of games
Source: [Populatiry of games on steam](https://www.kaggle.com/datasets/michau96/popularity-of-games-on-steam/data)  

**Description**  
The data for this data set was gathered from a website that updates every month to show the top games on the platform. Every observation in the data is aggregated information, since it is only updated per month. It shows the increase and decrease of player count for the game, peak player count.  

**Characteristics**  
- Number of feature: 7
- Number of observations: 83789
- start to end date: 2012 August to 2021 January (has no days, see description)


**Important features**  
- name = name of the game
- avg = average number of current playing user
- gain = difference in average from month-to-month
- peak = highest number of players at the same time
- avg_peak_perc = share of the average in the maximum value (avg / peak) in %



### Steam game releases
Source: [Steam game releases](https://www.kaggle.com/datasets/mexwell/steamgames/data)  

**Description**  
The data set has gathered data from steam game releases, with extensive information about every game. The information was fetched from the Steam API.  

**Characteristics**  
- Number of features: 39
- Number of observations: 71716
- start to end date: 1997-06-30 to 2025-04-14

**Important features**  
- Name = name of the game
- Release date = date where the game was released
- Peak CCU = peak total number of users
- User score = score of the review for the game, ranges from 0-5
- Reviews = review for the game
- Positive = positive rating of the game (thumb up on the platform)
- Negative = negative rating of the game (thumb down on the platform)
- Score rank = rank of the game by user score
- Windows/Mac/Linux = boolean value, if true it runs on the OS false otherwise
- Average playtime forever
- Average playtime two weeks
- Median playtime forever
- Median playtime two weeks
- Categories = category of the game ordinal value (Single-player, Multi-player)
- Genres = genre of the game as a list

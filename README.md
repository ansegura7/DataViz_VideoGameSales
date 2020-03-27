# Video Game Sales Analysis
Visual Analytics project to analyze and discovery insights of video game sales in recent years, with the high-level API <a href="https://plotly.com/python/plotly-express/" target="_blank" >plotly.express</a>.

![VG Sales Grouped by Publisher](https://raw.githubusercontent.com/ansegura7/DataViz_VideoGameSales/master/images/sales-grouped-by-publisher.PNG)

## Data Analysis
1. Video Games Sales per Year
2. Top 50 best-selling video games
3. Video Game Sales grouped by Platform
4. Video Game Sales grouped by Publisher
5. Sales Trends of Top 10 Publishers
6. Distribution of Video Game Sales
7. Evolution of Video Game sales by Genre

To view the data analysis, click on the <a href="https://ansegura7.github.io/DataViz_VideoGameSales/pages/VideoGameSales.html" >DataViz</a> link.

## Data
This dataset contains a list of video games with sales greater than 100,000 copies. Original data from <a href="https://www.kaggle.com/gregorut/videogamesales" target="_blank" >Kaggle</a>.

Fields include:
- Rank - Ranking of overall sales
- Name - The games name
- Platform - Platform of the games release (i.e. PC, PS4, etc.)
- Year - Year of the game's release
- Genre - Genre of the game
- Publisher - Publisher of the game
- NA_Sales - Sales in North America (in millions)
- EU_Sales - Sales in Europe (in millions)
- JP_Sales - Sales in Japan (in millions)
- Other_Sales - Sales in the rest of the world (in millions)
- Global_Sales - Total worldwide sales.

## Insights
- The year with the highest sales of video games was **2008**. It should also be taken into account that this was the year for which the most records were reported.
- The best-selling game is **Wii Sports** with approximately 80M copies. Also, the best-selling video game company is **Nintendo**.
- The 4 platforms that have contributed the most to video game sales are: PS2, PS3, X360 and Wii, closely followed by Nintendo DS and PS.
- As of 2013, the majority of video games sold were of the genres: Action, Role-Playing (RPG) and Adventure, closely followed by the genres: Sports and Shooter.
- Regarding the platforms that sold the most video games as of 2013, **PlayStation** (PS3, PS4 and PSV) is the clear winner, contributing approximately 40% of video games sold.
- The participation of games by gender is practically distributed uniformly by platform.
- Finally, how the video game genre trend has changed in each decade:
  - In the 1980s Platform games were the most played, with 32.5%, now they only represent 4.79%.
  - Instead, the Action genre is the most famous now with a 26.7% share.
  - The 1990s was one of the most balanced, where RPG games had more prominence (12.1%).

## Python Dependencies
``` python
  conda install -c plotly plotly_express
```

## Contributing and Feedback
Any kind of feedback/criticism would be greatly appreciated (algorithm design, documentation, improvement ideas, spelling mistakes, etc...).

## Author
- Created by Andrés Segura Tinoco
- Created on Mar 17, 2020

## License
This project is licensed under the terms of the MIT license.

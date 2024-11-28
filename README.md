![Screenshot (2)](https://github.com/user-attachments/assets/72ab3ec2-0f4e-4771-b06b-9e61840c56dc)

# Video Games Sales Analysis

## Table Of Content
- [Project Overview](#project-overview)
- [The Goal](#the-goal)
- [Tools Used](#tools-used)
- [The Process](#the-process)
- [Significant Insights](#significant-insights)
- [Interesting Insights](#interesting-insights)
- [Limitations](#limitations)
- [Conclusion](#conclusion)

## Project Overview
This analysis was performed on the Video game Sales Dataset. The dataset contains information on video game sales across various platforms and regions, with columns capturing different attributes of each game. 

## The Goal 
The goal of this project was to analyze video game sales data across different regions and identify key insights regarding game performance, platform popularity, genre trends, and publisher success. Here are a few insights we set out to discover and why we thought they would be beneficial to know.

1.	Total Global Sales
Purpose: To understand the overall market size and the aggregate revenue from all games.

2.	Regional Distribution of total Sales
Purpose: To understand the regional distribution of Global sales and gain insights into how revenue is spread across different markets. To highlight which regions contribute the most to overall sales and where potential growth opportunities lie, while exploring ways to improve sales in underperforming areas. It will also give insight on how to adjust product offerings, marketing campaigns, and distribution efforts based on regional demand and preferences. 

3.	Average Global Sales
Purpose: To gain insight into the typical performance of games across all markets, which will help set benchmarks for success and help us evaluate whether individual games are performing above or below average. We will also discover the overall sales health of video games and identify standout titles or underperformers.

5.	Platform Popularity
Purpose: To gain insights into the distribution of games across different gaming platforms, to discover the most popular platform, assess the concentration of the games on specific platforms, and identify opportunities to expand into underrepresented platforms. Additionally, this insight can guide future game development strategies by focusing on platforms with higher game counts or less competition.

6.	Top Ten Selling Games Globally
Purpose: To get a snapshot of the most successful games in terms of worldwide revenue and find standout games in the industry, often setting benchmarks for other games to follow. Analyzing these top performers can help identify successful trends, popular genres, and strategies that lead to high global sales. 

7.	Top five Publishers who contribute to the Highest Global Sales
Purpose: To assess the performance of different publishers, understand market share distribution, and identify top-performing publishers. It can help to spot trends in successful publishing strategies and determine which publishers consistently release high-grossing games. 

8.	Publishers with the highrest number of published games
Purpose: To understand which publishers are most prolific, indicating their market presence and product diversity. Publishers with a high number of games may have a broader reach across different genres and platforms, contributing to increased brand recognition. To also determine which publishers dominate in terms of game volume, allowing for strategic decisions in development and distribution.

10.	Top Sales Genres
Purpose: To determine which types of games generate the highest revenue. This analysis helps to understand market trends and consumer preferences, showing which genres are most popular and profitable.

## Tools Used
•	Power Query: Used for data transformation, enabling efficient cleaning, formatting, and analysis of the dataset.

•	Power BI: A powerful analytics tool that facilitated the creation of interactive visualizations and dashboards for a comprehensive understanding of the data.

## The Process
Data Cleaning and Preparation:
The raw data was first cleaned and transformed to ensure consistency. This involved handling missing values, removing blank spaces, removing duplicate values, identifying outliers and standardizing sales values by converting them into millions for easier analysis.

Data Transformation:
The data was loaded on to power query to be transformed after it was cleaned. We transformed the data by ensuring the data types were consistent with the data, removed duplicates and renamed coloumns.

Data Modeling:
The data was modelled into a fact table for sales data; game sales by region and globally, and one dimension table containing game attributes; platform, genre, publisher, rank the release year data. This star schema was implemented in Power BI, allowing for efficient querying and reporting.

Analysis and Reporting:
Key metrics such as Total global sales, Total Regional sales, Count of Platform, Count of Publisher, Count of Genre, Average of each of the Total Sales’, were calculated. Measures and visualizations were built in Power BI to gain several insights.

## Significant Insights

1.	Total Global Sales
Insight: The total global sales amount to $8.92 billion, representing the cumulative revenue generated by all games in the dataset. This figure underscores the significant economic scale of the gaming industry, reflecting the overall market impact and success.

2.	Regional Distribution of total Sales
   
The distribution of global sales across regions reveals distinct market dynamics:
•	North America leads with 49.27% of global sales, underscoring its dominant role in the gaming market and reflecting a strong consumer base and purchasing power.
•	Europe accounts for 27.3% of global sales, indicating a significant market presence and suggesting strong regional interest and engagement with gaming products.
•	Japan holds 14.48% of the market, reflecting its important but smaller share compared to North America and Europe, which may be influenced by unique local preferences and market conditions.

•	Other Regions contribute 8.95% to global sales, highlighting emerging or smaller markets that still contribute to the overall revenue.
This distribution highlights key areas of strength and potential growth opportunities. North America's substantial share suggests it as a focal point for major game releases and marketing efforts. Europe's considerable contribution indicates a strong market presence that could benefit from tailored regional strategies. Japan's share points to specific regional trends that might require localized approaches. The "Other Regions" category, while smaller, represents growth potential and opportunities to expand into less saturated markets.
Understanding these regional dynamics is crucial for shaping market strategies, optimizing resource allocation, and aligning product offerings with regional consumer demands.

4.	Average Global Sales
Insight: The average global sales of $537.4 thousand suggests that, on average, each game in the dataset generates a moderate level of revenue. This metric provides insight into the typical financial performance of games and serves as a benchmark for evaluating success. Games that exceed this average are performing well above the norm, while those below it may be underperforming. This average indicates a general revenue range that can help stakeholders understand the market's economic dynamics and set realistic expectations for game sales performance. 

5.	Platform Popularity
   
 The top ten platforms with the largest number of games are:
•	DS
•	PS2
•	PS3
•	Wii
•	X360
•	PSP
•	PS
•	PC
•	XB
•	GBA

These platforms represent the most prolific systems in the dataset, showcasing a broad range of titles and indicating their significant role in the gaming market. A high number of games on these platforms may reflect their popularity, extensive user base, and long market presence. This information helps in understanding market saturation, evaluating platform-specific performance, and guiding strategic decisions for future game development and distribution. Market Presence: Platforms like PS2 and Wii, which appear prominently on the list, were highly successful and influential during their peak. Their large number of games suggests strong market presence and developer support.

6.	Top Ten Selling Games Globally
   
   The top 10 selling games globally are:
1.	Wii Sports
2.	Grand Theft Auto V
3.	Super Mario Bros.
4.	Tetris
5.	Mario Kart Wii
6.	Wii Sports Resort
7.	Pokémon Red/Pokémon Blue
8.	Call of Duty: Black Ops
9.	Call of Duty: Modern Warfare 3
10.	New Super Mario Bros.
    
From the list of the top 10 selling games globally, several key patterns and trends emerge:
1.	Platform Impact: The Wii and Nintendo platforms are prominently featured, with multiple titles such as "Wii Sports," "Mario Kart Wii," and "Wii Sports Resort" among the top sellers. This suggests that the Wii's innovative gameplay and broad appeal significantly contributed to its success.
2.	Genre Diversity: The top 10 list includes a mix of genres, such as sports;Wii Sports, action; Grand Theft Auto V,  puzzle; Tetris, and shooters, Call of Duty series. This diversity indicates that multiple genres can achieve high sales, appealing to a wide range of players.

6.	Top five Publishers who contribute to the Highest Global Sales
   
	  The top five publishers contributing to total global sales are:
1.	Nintendo
2.	Electronic Arts
3.	Activision
4.	Sony Computer Entertainment
5.	Ubisoft
   
Publisher Dominance: The presence of Nintendo, Electronic Arts, Activision, Sony Computer Entertainment, and Ubisoft among the top contributors indicates that a few major publishers dominate the gaming market. These companies are key players in shaping industry trends and generating substantial revenue.
Diverse Game Portfolio: The diversity among these publishers highlights that offering a wide range of game types can be a successful strategy. This diverse portfolio helps attract a broad audience and meet various market demands.

7.	Publishers with the highest number of published games
   
 The publishers with the highest number of published games are:
 
1.	Electronic Arts
2.	Activision
3.	Namco Bandai Games
4.	Ubisoft
5.	Konami Digital Entertainment
   
Market Penetration: These publishers have managed to penetrate various gaming segments by releasing numerous titles across different genres and platforms. Their large number of games indicates a significant market presence and ability to cater to diverse player preferences.
Diverse Portfolios: The extensive game catalogs of these publishers reflect their commitment to offering a wide range of gaming experiences. This diversity helps them reach different demographics and maintain a strong foothold in the competitive gaming industry.

8.	Top Sales Genres
   
The top sales genres are:
1.	Action
2.	Sports
3.	Shooter
4.	Role-Playing
   
These genres dominate the sales charts, reflecting key trends in player preferences. Action games lead in popularity due to their engaging and dynamic gameplay. Sports games are also highly favored, showcasing the appeal of sports simulations and franchises. Shooter games rank highly, indicating a strong interest in competitive and adrenaline-driven experiences. Finally, role-playing games are significant for their rich storylines and character development, catering to players who enjoy immersive narratives. This pattern highlights the genres that resonate most with gamers and shapes the overall gaming market.

## Interesting Insights
A notable insight is the contrast between publishers with the most games and those with the highest global sales. Publishers like Electronic Arts and Activision, with extensive game libraries, aim to reach broad audiences, while top sales leaders such as Nintendo focus on a few blockbuster titles for significant revenue. This highlights a strategic trade-off: a large game catalog increases market presence, but substantial sales often come from a select few high-performing games.

The top sales genres in the dataset which are: action, sports, shooter, and role-playing, reveal key trends in gaming preferences. Action games, including high-energy titles with engaging gameplay, lead the sales charts, indicating a strong player interest in dynamic and immersive experiences. Sports games also perform exceptionally well, reflecting the widespread appeal of sports simulations and franchises. Shooter games, known for their competitive and adrenaline-pumping gameplay, also rank high, highlighting their popularity among gamers. Role-playing games, with their deep storylines and character development, complete the list, showcasing a demand for rich, narrative-driven experiences. This pattern demonstrates that players gravitate towards genres that offer excitement, competition, and engaging stories, shaping the gaming market and influencing game development strategies.

The dataset also reveals that certain platforms and publishers have a significant impact on genre popularity and overall sales. For instance, Nintendo's dominance in sales is linked to its successful franchises in genres like action and role-playing, which have seen substantial success on platforms like the Wii and DS. Similarly, platforms with extensive game libraries, such as the PS2 and DS, offer a wide range of genres, contributing to their high number of published games.

## Limitations
One major challenge encountered during the project was the issue of incomplete dates. Some records and games in the dataset were missing published dates and were recorded as "N/A." This limitation prevented us from performing any time-based trends or analyses, as the lack of complete data compromised the accuracy of our insights. Consequently, any conclusions drawn from the available dates data may not fully reflect true patterns or trends.

## Conclusion
Overall, the project provided valuable insights into global sales, publisher contributions, and genre popularity in the gaming industry. While some questions about time-based trends and comprehensive analysis were limited by incomplete data,key patterns were successfully identified, such as the dominance of certain genres and platforms, and the strategic impact of major publishers. The process was engaging and enlightening, revealing how market strategies and player preferences shape the gaming landscape. Despite the challenges, the findings offer a solid foundation for understanding the dynamics of game sales and publisher influence, contributing to a richer perspective on the industry.













# GLOBAL-VIDEO-GAME-SALES-OVERVIEW-2008-2013-
![image](https://github.com/user-attachments/assets/871cf2db-542a-4304-9310-da527b0d2102)

Introduction
This dataset contains global video game sales information across various platforms, genres, and publishers. It includes sales performance in key regions - North America, Europe, Japan, and others - alongside metadata such as release year, game genre, and publisher. The goal is to analyze market trends, regional preferences, and top-performing games to better understand the video game industry's dynamics.


Data Cleaning Procedure
To prepare the dataset for analysis, the following steps were taken:
Missing Values
Checked for and addressed null values in key fields such as Year, Genre, and Publisher using imputation or removal where appropriate.
Data Type Correction
Converted Year to integer or datetime format for chronological sorting and analysis.
Ensured sales figures (NA_Sales, EU_Sales, etc.) are in numeric format.
Duplicate Entries
Removed duplicate rows based on Name and Platform combinations to avoid inflated results.
Standardization
Standardized text fields (e.g., Platform, Genre, Publisher) to maintain consistent naming and formatting.
Sales Validation
Verified that Global_Sales equals the sum of regional sales to ensure data consistency.



Dependent Variable
Global_Sales



Independent Value
Rank (can be excluded from modeling but useful for ordering)
Name (not useful for modeling acts as an identifier only)
Platform (e.g., PS4, Xbox, PC categorical)
Year (release year numerical or categorical bucket)
Genre (e.g., Action, Sports categorical)
Publisher (e.g., Nintendo, EA categorical)
NA_Sales (North America numeric)
EU_Sales (Europe numeric)
JP_Sales (Japan numeric)
Other_Sales (Rest of the world numeric)



Story of the Data
This dataset captures global video game sales across various platforms, publishers, and genres from 2008 to 2013. It includes sales figures broken down by region (NA, EU, JP, Others), platform types (e.g., PS2, X360), 
and key metadata like publisher and game title. The purpose is to uncover sales trends, consumer preferences, and performance drivers in the video game industry during this period.



Industry Type
Video Game / Interactive Entertainment Industry
Project Stakeholders
Marketing Teams
Game Publishers (e.g., Nintendo, EA)



Potential Questions
What year recorded the highest global sales and why?
Which genre performed best globally and across regions?
What is the trend of global game sales from 2008 to 2013?
Which platform contributed most to global sales?
How do publishers rank by global sales volume?
What are the top 10 best-selling games, and what platforms/genres do they belong to?
Is there a correlation between platform type and sales volume?
Which region (NA, EU, JP, Other) dominates game consumption?
How do publisher market shares compare?
Has consumer preference for genres changed over time?



Observation
1.2008 peak suggests a golden year possibly due to new console launches or hit titles.
2.Sales decline post-2008 could indicate market saturation, lack of innovation, or economic shifts.
3.Action genre's dominance reflects strong market interest in fast-paced, engaging gameplay.
4.PS2's high usage shows the platform's extended lifecycle and strong install base.
5.Nintendo's lead in publishing correlates with both hardware and software dominance (e.g., Wii Sports).
6.Top games are family-friendly or franchise-based, suggesting brand trust and replay value matter.
7.Shooter and Sports genres maintain high popularity, making them reliable categories for investment.
8.Sony and Microsoft platforms also show strength, meaning cross-platform development is beneficial.
9.Limited performance in niche genres like Simulation indicates lower mass appeal but possible niche loyalty.
10.Sales leadership by a few publishers suggests high industry consolidation small studios may struggle without backing.


Recommendation
1.Study what drove 2008's peak (e.g., marketing, innovation) and replicate patterns where possible.
2.Revitalize declining trends by exploring new genres, remakes, or innovative gameplay features.
3.Continue investing in Action titles, but blend elements from Sports or Role-Playing for diversity.
4.Support cross-platform development to tap into user bases of both legacy and modern consoles.
5.Target partnerships with top publishers or study their distribution/marketing models.
6.Bundle more family-oriented games to recreate success like Wii Sports.
7.Capitalize on franchise loyalty, especially for sequels or spin-offs of best-selling titles.
8.Diversify portfolios, balancing high-performing genres with niche ones to serve varied audiences.
9.Track user data and feedback for real-time genre interest shifts to stay ahead of demand.



Conclusion
Sustaining growth in the gaming industry requires a balanced approach rooted in data, innovation, and strategic partnerships. Analyzing the success drivers of the 2008 sales peak such as strong marketing and genre-defining innovation can provide a blueprint for future launches. Revitalizing interest through remakes, genre hybrids, and unique gameplay experiences will attract both nostalgic and new audiences. Continued investment in popular genres like Action, while blending in elements from Sports or RPGs, can broaden appeal. Embracing cross-platform development and studying top publishers' strategies can unlock wider market reach. Moreover, leveraging franchise loyalty, bundling family-friendly titles, and monitoring real-time user feedback will keep portfolios aligned with evolving consumer preferences.

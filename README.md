# Exploratory Analysis of Video Games Sales Data

This project aims at evaluating Videogames sales data, up-to-date till 2024, and achieve valuable insights in the process. Several trends that can be observed through the analysis are expanded on at each step.

Eventually, K-Prototype clustering is performed in the end, to identify key differences and hallmark properties of games that have been performing really well (and ones that are not), in sales, based on features in the dataset. Clustering also helps to bring out previously unforseen patterns in the data, that may be affecting sales.

I recommend going through the notebook, as the results and their analysis has been done in much detail there.

## Visualisation and Exploratory Analysis
Visualisation is done based on quite some criteria:

1. Top Selling Games: A brief analysis of the top ten games, based on franchises.
2. Platform-Wise Top Selling Games: A look into the overall top platforms, with respect to a sales of a single game.
3. Publisher Analysis: An overview of top publishers, their best titles, and the brief dive into possible reasons of success.
4. Genre Based Analysis: A Study of various different genres such as Action, Adventure, Platformer, etc.. and their impact on sales.
5. Release Dates and Sales: A Visualisation and Analysis of effects of release dates on games, and also their overall evolution over the years.
6. Critic Scores: A study of impact of critic scores on game sales.

## Regional Sales Data based Clustering

Clustering is performed, using the K-Means algorithm, based exclusively on regional sales data. The resulting cluster portray quite some information:
* Region Based: Different region show different kinds of clusters being dominant.
* Sales Based: Along with regions, there is also a clear difference in clusters based on sales performance.

## Sales & Categorical Class based Clustering

Clustering is now done using all the additional features available, including genre, consoles and critic scores. For this purpose, the K-Prototype clustering algorithm is used. 
Finally, three main clusters emerged, with distinct properties. An analysis for further profiling has been done to identify them, based on each feature. The detailed analysis is provided in the notebook, and the clusters can be identified (very broadly) as:
0: High Chances of Success (NA, PAL)
1: Average Chance of Success (NA, PAL) but Highly suitable for JP
2: Low Chance of Success

[I could probably have named them better, I apologise for the same]

## Conclusion
Based on the above project, several minute business observations can be made. But through the broader lens, my conclusion is that management and analysis play an essential role in the game industry, where it seems that the "chaos" cannot be eliminated, since it is essential to continuously push boundaries, to embed the sparks of creativity and passion into the entire process of creating the project, throughout art, development, marketing, etc.. In such a situation, it becomes essential to assess the markets, and at the same time maintain employee morale, since both of them are essential to achieve any goal in the gaming industry, be it a groundbreaking title with an amazing sales record, or an amazing experience that leaves a lasting impression on the player for the remainder of their lives.

It was a blast making this project, and I hope it is an interesting read, for well, anyone interested!

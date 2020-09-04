# Lichess
[Lichess](https://lichess.org) is a free and open-source Internet chess server run by a non-profit organization of the same name. Anyone can play anonymously, although players may register an account on the site to play rated games
The dataset contains 20,000+ Lichess Games, including moves, victor, rating, opening details and more.

## **General Info**

This is a set of just over 20,000 games collected from a selection of users on the site Lichess.org, and how to collect more. I will also upload more games in the future as I collect them. This set contains the:

* Game ID;
* Rated (T/F);
* Start Time;
* End Time;
* Number of Turns;
* Game Status;
* Winner;
* Time Increment;
* White Player ID;
* White Player Rating;
* Black Player ID;
* Black Player Rating;
* All Moves in Standard Chess Notation;
* Opening Eco (Standardised Code for any given opening, list here);
* Opening Name;
* Opening Ply (Number of moves in the opening phase)\

For each of these separate games from Lichess. I collected this data using the Lichess API, which enables collection of any given users game history. The difficult part was collecting usernames to use, however the API also enables dumping of all users in a Lichess team. There are several teams on Lichess with over 1,500 players, so this proved an effective way to get users to collect games from.

Possible Uses

Lots of information is contained within a single chess game, let alone a full dataset of multiple games. It is primarily a game of patterns, and data science is all about detecting patterns in data, which is why chess has been one of the most invested in areas of AI in the past. This dataset collects all of the information available from 20,000 games and presents it in a format that is easy to process for analysis of, for example, what allows a player to win as black or white, how much meta (out-of-game) factors affect a game, the relationship between openings and victory for black and white and more.

This is analysis we'll answer some important questions. This analysis composed two parts: 
* **Statistical Summary**
* **Data Visualization** 
In first part we discover some statistical summaries like **Mean, Median, Interquartiles, Standard Deviations, Skewness, Kurtosis and etc**.
Then with Data Visualization going to find patterns and insight among data. Some plots are listed Below
* **Barplot**
* **Countplot**
* **Donutplot**
* **Scatterplot**
* **Histogram** 

Some of plots are listed below, for more information and full analysis, pls open notebook and study analysis like proportion of winners, frequent times, play mode, game status and ...
![](https://github.com/SoroushGhaderi/Lichess_Data_Analysis/blob/master/figures/Barplot_of_frequntly_of_initial_and_addition_time.png)
![](https://github.com/SoroushGhaderi/Lichess_Data_Analysis/blob/master/figures/Barplot_of_openings.png)
![](https://github.com/SoroushGhaderi/Lichess_Data_Analysis/blob/master/figures/Histogram_of_turns.png)
![](https://github.com/SoroushGhaderi/Lichess_Data_Analysis/blob/master/figures/Donut_plot_of_winner_types.png)
![](https://github.com/SoroushGhaderi/Lichess_Data_Analysis/blob/master/figures/Barplot_of_times.png)

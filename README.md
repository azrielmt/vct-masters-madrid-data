<img src="https://liquipedia.net/commons/images/9/9d/VCT_Masters_Madrid_allmode.png" width="350" />

### VALORANT Masters Madrid is the first international tournament of the 2024 VALORANT Champions Tour Schedule. A total of 8 teams qualified, 2 from each of the four international leagues, being Americas, EMEA, Pacific and China qualified from the season's [Kickoff](https://liquipedia.net/valorant/VCT/2024) tournaments. 

The qualified teams are as follows:

Americas:
- **Sentinels** (*Kickoff Winner*)
- **LOUD** (*Kickoff Runner-up*)

EMEA:
- **Karmine Corp** (*Kickoff Winner*)
- **Team Heretics** (*Kickoff Runner-up*)

Pacific:
- **Gen.G** (*Kickoff Winner*)
- **Paper Rex** (*Kickoff Runner-up*)

China:
- **EDWard Gaming** (*Kickoff Winner*)
- **FunPlus Phoenix** (*Kickoff Runner-up*)

The 8 team tournament featured a Swiss Stage that ultimately eliminated 4 teams and then a Playoff Stage featuring **Gen.G, Paper Rex, Sentinels and LOUD**. Ultimately, Sentinels, representatives from the Americas league, win the tournament that also featured a prize pool of $500,000.

<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fpiks.eldesmarque.com%2Fthumbs%2F660%2Fbin%2F2024%2F03%2F25%2F53608027207_56471550ec_c.jpg&f=1&nofb=1&ipt=646fb03fb78eb04bba9bafcf2452c1fbe2772085e24af36c80413f9118e496e6&ipo=images" width="500" />

While VALORANT is a complex game, statistics of players are one thing, but strategy, map pick, agent pick and the synergy of a team is another as well. Let's take a look comparing player and team data, overall performance and frequency of a map being picked by data cleaning and using visualizations to see.

# Glossary
From the [Kaggle](https://www.kaggle.com/datasets/rakeshkudmulwar7/masters-madrid-valorant-champions-2024) page, the following performance metrics are used:
- Kills (K)
- Deaths (D) 
- Assists (A)
- Kill/Death Ratio (KD) 
- Kill/Death/Assist Ratio (KDA)
- Average Combat Score per map (ACS/Map)
- Kills per map (K/Map)
- Deaths per map (D/Map)
- Assists per map (A/Map)

# Process
- Reviewed the data sets while trying to figure out what questions to answer.
- Cleaned the 'Player Statistics' dataset by clearing out any player duplicates and removing irrelevant columns.
- Sort out the DataFrame in order by "Kills".
- Created a bar chart showing the amount of "Kills" per player.
- Reduced a dataframe to show a player's "Kills" and "Deaths".
- Combined the columns of the player and their team into one column.
- Made a bar chart comparing every player's "Kills" and "Deaths".
- Made a new bar chart after reducing the dataframe to Master Madrids' Playoff teams only.
- TBD

# Conclusion

# Sources
- https://www.kaggle.com/datasets/rakeshkudmulwar7/masters-madrid-valorant-champions-2024
- https://liquipedia.net/valorant/VCT/2024/Stage_1/Masters

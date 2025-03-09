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
- Sort out the DataFrame in order by "Kills". Did the same for "Deaths", "Assists", "ACS", "KDA", "K/Map", "D/Map", "A/Map".
- Created a bar chart showing the amount of "Kills", "Deaths", "Assists", "ACS", "KDA", "K/Map", "D/Map", "A/Map" per player.
- Reduced a dataframe to show a player's "Kills" and "Deaths".
- Combined the columns of the player and their team into one column.
- Made a bar chart comparing every player's "Kills" and "Deaths".
- Made a new bar chart after reducing the dataframe to Master Madrids' Playoff teams only.
- Found the amount of players in the playoffs only who had a positive K/D ratio.
- Found the amount of players in the playoffs only who had a negative K/D ratio.
- Merged datasets for Maps to create a larger dataframe.


Later:
- Save visuals. 
- Simple pie charts for maps played. 
- Combine maps played and banned for a complete DF.
- More pie charts / other charts?

# Conclusion
- Zekken had the most kills out of everyone at Masters Madrid, totaling 381 kills and was a major factor to Sentintels going far and winning the tournament.
- Out of the 20 players in the playoffs, 13 players had a postive K/D ratio, 65%. Out of both Grand Final teams, Sentinels had two players (Zellsis and Sacy) with a negative K/D ratio and Gen.G had only one (Lakia). 
- While Zellsis and Sacy had negative K/D ratios, the total Kill count still had Zekken with the most amount of kills, with TenZ and johnqt right after. This definitely is a factor as to why Sentinels won this tournament in the end. However, there is a thought that these counts could also be decided with the fact that Sentinels may have played more rounds and that they were coming out of the lower end of the bracket. This may also be the case with Paper Rex, as they faced Sentinels in the Lower Final.
- In order, TenZ had the most amount of assists in this tournament, with 226 assists with Zellsis (172) and Sacy (169) following, which shows how the importance of the players despite Zellsis and Sacy's negative K/D ratio. TenZ also led the "A/Map" statistic, which factors into why he has the most assists out of everyone.
- ACS, which is the cumulation of Kills, Damage and Non-Damaging Assists in a map (not only calculates KDA but also factors with abilities used), Zekken led this category, but a bunch of other players who were eliminated early followed him, including ZmjjKK, N4RRATE, MiniBoo and Autumn. This category shows how impactful one player can be on a team, despite a team's result.
- Speaking of N4RRATE from Karmine Corp, he was very impactful as he led best KDA as well, with two LOUD players behind him, being Tuyz and Less. This is purely statistic and does not factor in everything else. 
- Zekken and MiniBoo with the best "K/Map" statistic with N4RRATE right behind both, which shows they were able to rack up as many kills for their respective teams in the times they were playing. 
- Autumn from FunPlus Phoenix unfortunately led "D/Map", which meant he was killed more than anyone else in the tournament during a map.
Maps next...


# Drawbacks and Questions
While this is a helpful dataset that shows meaningful statistics, there are still a lot more questions that can be made. While statistics can be one thing, VALORANT also requires a lot of other factors to a team's success. 
- There was not enough information to draw conclusions on maps, such as what teams played on what maps, what maps they banned and what maps they lost on the most. While this information can be gathered elsewhere, the purpose of this project is to find out conclusions using this dataset alone.
- There was not enough information on use of Agents, such as what agents players used the most, agents used the least, agents used the most and least on certain maps and potential head to head comparisons on specific players using the same agent on a certain map or game. In VALORANT, certain agents can perform will on certain maps while some cannot. It also can be a factor of the current meta (state of the game in terms of who is a high tier agent to use versus a low tier agent.)
- Numbers can be skewed toward the Grand Final teams as they played the most in this tournament compared to a team who were knocked out during the Swiss stage. 
- As mentioned before, VALORANT has a lot more factors than just KDA and ACS. A team's performance also weighs on coaching, pure experience on the international stage, team cohesiveness, time and preparation and many more factors. For example, TenZ has won a Masters tournament before and Sacy has won a Champions tournament before. Their experience was pivotal to the Sentinels' success compared to a team like Karmine Corp, who doesn't have the same level of experience. 

# Sources
- https://www.kaggle.com/datasets/rakeshkudmulwar7/masters-madrid-valorant-champions-2024
- https://liquipedia.net/valorant/VCT/2024/Stage_1/Masters
- https://tracker.gg/valorant/articles/what-is-acs-in-valorant-and-how-does-it-work


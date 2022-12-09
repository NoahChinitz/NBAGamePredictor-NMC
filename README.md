# NBAGamePredictor-NMC

Being the avid basketball fan that I am, I wanted to do something involving basketball data. Fortunately, the National Basketball Association (NBA) provides an API that contains all game data, team data, and player data. So, I wanted to create a neural network that could predict if the home team is going to win any given game. 

Since the NBA API is a massive database that contains a lot of information I do not care about, I am going to be taking advantage of *[nba_api](https://github.com/swar/nba_api)* on GitHub and the ******************[Basketball Dataset](https://www.kaggle.com/datasets/wyattowalsh/basketball)****************** on Kaggle. The nba_api is a framework for interacting with the NBA API using Python. The Basketball Dataset already does most of my work for me, by compiling all game, team, and player data.

I will be taking in data post-NBA/ABA merger. The data will include minutes played, field goals attempted, three point field goals attempted, free throws attempted, rebounds, assists, steals, blocks, turnovers, and personal fouls for both teams in the match. It will then attempt to predict if the home team won that game or not.

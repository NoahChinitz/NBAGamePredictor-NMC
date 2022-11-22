# CelticsPredictor-NMC

Being the avid basketball fan that I am, I wanted to do something involving basketball data. Fortunately, the National Basketball Association (NBA) provides an API that contains all game data, team data, and player data. So, I wanted to create a neural network that could predict if the Boston Celtics would win against a given opponent during the 2021-2022 season. 

Since the NBA API is a massive database that contains a lot of information I do not care about, I am going to be taking advantage of *[nba_api](https://github.com/swar/nba_api)* on GitHub and the ******************[Basketball Dataset](https://www.kaggle.com/datasets/wyattowalsh/basketball)****************** on Kaggle. The nba_api is a framework for interacting with the NBA API using Python. The Basketball Dataset already does most of my work for me, by already compiling all game, team, and player data.

I want to start by being able to take in information such as team win/loss record, team win/loss record against a specific team, and who is the home team in order to make the prediction. If that goes well, I would like to try and expand it to take in more granular data.

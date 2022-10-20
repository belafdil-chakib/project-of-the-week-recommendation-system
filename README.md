## project-of-the-week: Recommendation Systems

Check the following link for more detail about the project: [DataTalksClub](https://github.com/DataTalksClub/project-of-the-week/blob/main/2022-10-19-recommenders-1.md)

## Goal 

Create a recommendation system for steam player based on their previous purchase.

The data can be found here: [Kaggle-Steam Video Games](https://www.kaggle.com/datasets/tamber/steam-video-games)

## Cleaning and EDA

The data has some duplicate that had been cleaned and the feature "Hours" has been feature engineered in order to illustrate the score of likeliness for each user for a particular game.
It is min-max scaled because games need different duration to be completed otherwise long games would have a higher score.

Drawback: If a game hasn't been finished by any user, then the "likeliness" will be wrongly computed. To improve it it would require to have a side table of game duration for each game.

Check [Jupyter Notebook here!](Cleaning%20an%20EDA.ipnyb)
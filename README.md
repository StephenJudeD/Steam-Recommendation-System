# Steam-Recommendation-System
I present a small recommendation system for the Steam game store database that utilizes Feature Extraction

The recommendation system will be based on the game name, developer, genre, tags and description. 
The dataframe contains 27,000 games. 
Since not all games can meet their tags or players' expectations, I decided to remove games with a difference between positive and negative ratings less than 10. One of the options might not be to completely remove these games from the dataframe, but to remove these games from the recommendations, which will allow you to search games similar to them, but with a positive rating. But the first method allows you to reduce the dataframe, so I could not resist deleting. 
Games without English translation have been removed, as recommendations for such games are likely to be incorrect.


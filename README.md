## Steam and Twitch Capstone
My capstone project for the General Assembly. A partner and I created a database of video game data from [Steam](https://store.steampowered.com/) and [Twitch](https://sullygnome.com/)
in order to run analysis on two relationships. Firstly, game ratings and genre saturation, and the second being player behavior and twitch viewership. This page contains the repository
of CSVs created from the data and the Power BI and Powerpoint used to present our insights. This data was gathered during August/September of 2024.

## Repository
The CSV files correspond to tables from the Steam directory dataset and are compressed into ZIP files for easy downloading. 
You can unzip and import them into a database or use them as is for analysis.

- **steam_directory.csv**: Main table containing details about the games, such as title, release date, and other metadata.
- **genres.csv**: Genres assigned to each game.
- **tags.csv**: Tags associated with each game, such as "Indie", "Action", etc.
- **reviews.csv**: Review data for the games, including Steam ratings and review counts.
- **game_performance.csv**: Insights gathered from a sample of Steam users such as playtime_forever (minutes), playtime in two weeks (minutes), and owners who have not played.
- **Player_behavior.csv**: Data gathered on Steam users like library size, backlog size, and playtime_forever (minutes).
- **31_day_global_top_sellers.csv**: Insights gathered from the Steam trending pages on the top sellers over 31 days. 
- **365_day_twitch_data.csv**: Historical Twitch data sourced from [Sullygnome.com](https://sullygnome.com/) on the top 3,500 games over 365 days.
- **30_day_twitch_data.csv**: Historical Twitch data sourced from [Sullygnome.com](https://sullygnome.com/) on the top 300 games over 30 days.
- **14_day_twitch_data.csv**: Historical Twitch data sourced from [Sullygnome.com](https://sullygnome.com/) on the top 4,000 games over 14 days.
- **categories.csv**: Information about the different Steam categories that games belong to (e.g., "Single-player", "Full controller support", etc.).

## Insights

These files contain our insights presented in a Power BI dashboard and a Powerpoint presentation. We found that multiplayer games, especialy those designed around e-sports, had high playtime numbers which denoted good retention of players. On the twitch front, we found there was some overlap between games played and watched, especially e-sports titles. Though, there were exceptions to this rule, some less played titles performed well on Twitch. Overall, we recommended stakeholders to invest in free-to-play e-sports based titles, partnering with Twitch streamers to introduce new players into their ecosystems, and using broadcast e-sports leagues to drive player retention. The files are also zipped 
for easy downloading. 

-**Capstone_Wes_PBI**: The .pbix file for the capstone
-**Capstone_Wes_pdf**: A PDF file for the capstone
-**Steam_and_Twitch_Capstone**: A Powerpoint presentation made to provide context for our insights.

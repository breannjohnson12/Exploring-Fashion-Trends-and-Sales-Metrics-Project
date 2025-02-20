## 🎧 Spotify-Listening-History-Analysis

*This project analyzes personal Spotify listening history to uncover listening patterns, favorite artists, and music consumption habits. Using Python and data analysis libraries, it provides insights into music listening behavior over time.

*The dataset I used is a Spotify listening history dataset, containing information about tracks played, timestamps, play durations, platforms, and user behaviors (e.g., shuffle, skipped, reasons for starting/ending tracks). 
* I approached this project by using the data analysis cycle consisting of:
  * Forming/Asking Questions
  * Data Wrangling
  * Data Cleaning
  * Exploratory Data Analysis (EDA)
  * Data Visualization
  * Drawing Conclusions/Data Interpretation

 **Through my analysis I answered the following questions:**

 * How does listening behavior change over different times of the day, days of the week, or months?
 * Are there peaks in streaming activity (e.g., morning vs. evening listening)?
 * Which tracks have the longest average play duration?
 * Who are the top artists based on frequency of plays?
 * Does the listening behavior differ across different platforms (if available) such as the web player versus mobile?
 * What is the distribution of play durations in minutes, and are there outliers or tracks with unusually low or high play durations?
 * Is there a relationship between play duration and whether a track was skipped?
 * Which albums have the highest engagement, and does the context of play (e.g., autoplay vs. curated selection) vary by album?
 * How often do users skip tracks, and are there patterns in the songs that tend to be skipped?

## 🎧 Insights
1. Creating a visualization that displays listening behavior by hour of day, I saw that listening activity experiences clear peaks around the afternoon/evening time period. This time period is usually when people are most active whether it's running errands, working, or even being at the gym. This means that people listen to more music when they are going about their day and completing daily activities.
![image](https://github.com/user-attachments/assets/cc965c59-b79f-4625-a8da-a358eec3d9fc)
2. The platform usage visualization shows what method users are using to use the Spotify player. Mobile usage is the highest, Android is the majority with IOS next. Web player shows minimal usage
![image](https://github.com/user-attachments/assets/d24258a7-4cc1-4f53-8361-a2c9b0019449)
3. Most Played Artists are as follows:

artist_name
* The Beatles           13530
* The Killers            6748
* John Mayer             4797
* Bob Dylan              3790
* Paul McCartney         2685
* Led Zeppelin           2470
* Johnny Cash            2467
* The Rolling Stones     2367
* Radiohead              2295
* The Black Keys         2221

The Beatles are a popular artist in listening history with over 13,000 plays
The Killers and John Mayer make up the top 3 alongside The Beatles
The top 10 shows a strong preference for rock and alternative genres
Classic rock artists (Led Zeppelin, The Rolling Stones) feature prominently

4. Low Skip Rate at around 5.25%
This shows that the user has a well-curated playlist that matches their taste making them have to skip songs a lot less. They are more careful with music selection in their liked songs tab or playlists. Actively chooses what to listen to rather than relying on the shuffle feature.
5. Top 10 Albums by listening time
![image](https://github.com/user-attachments/assets/e83185ac-baf0-4ee8-8cfd-9d06ddeface5)
"The New Abnormal" and "The Beatles" albums show the highest total listening time
This user has a mix of classic albums (Abbey Road, Blood On The Tracks) and modern releases (Imploding The Mirage)

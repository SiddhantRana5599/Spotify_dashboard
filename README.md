Overview: The Spotify Dashboard project aims to create a dynamic and interactive user interface for displaying my personalized Spotify data for the last 6 years(2019-2025). The dashboard pulls information from my Spotify data(JSON files) to showcase real-time user statistics such as top tracks, favorite artists, listening history, song end reason and in which part of the day I listened the most. The interface is designed to provide a user-friendly experience while offering in-depth insights into my music preferences and activity.
![dashboard](https://github.com/user-attachments/assets/88cef16d-5370-4a5d-893d-687905a657f5)

Overall Listening:

Significant Usage: I have listened to a substantial amount of music, with 23.51K total songs played and 48.38K total minutes (approximately 806 hours).
Diverse Catalog: I have explored a wide range of music, with 989 unique artists, 2134 unique songs, and 1936 unique albums. This suggests a broad taste in music.
Key Insights:

Listening Trends Over Time:

Peak in 2022: The "Songs per Year" graph shows a clear peak in listening activity in 2022. This could be due to various factors like more free time, specific events, or simply a period of heightened music discovery.
Decline After Peak: There's a noticeable decline in listening after 2022, though there's a slight uptick towards 2024.
Top Content:

Top Songs: "Hold On" is the most played song with 154 plays, followed by "Can't Let You Go" (122 plays). This highlights my favorite tracks.
Top Artists: Pritam is the most listened-to artist by a significant margin (756 plays), followed by Amit Trivedi (641 plays) and Justin Bieber (533 plays). This suggests a strong preference for these artists.
Listening Behavior:

Song End Reasons:
"Trackdone" (song finished playing) is the most common reason for a song ending (40.94%), which is normal.
"Fwdbtn" (forward button) accounts for a substantial portion (21.77%), "Endplay" (I played another song) makes up 20.68%. and "Backbtn" (backward button) accounts for (6.91%)and indicating that I frequently skips songs. This could mean I may be exploring new music, not enjoying certain parts of songs, or using playlists with some unwanted tracks.
Parts of Day:
"Afternoon" is the most popular time for listening (37.20%), followed by "Morning" (26.08%). This suggests that I listens to music during the day, likely during work, study, or commuting.
Platform Usage:

Dominant Platform: The dashboard indicates usage across multiple platforms (Android, Webplayer, Windows) with Android being the dominant platform, followed by Windows and webplayer.
Key Questions and Further Analysis:

Reasons for 2022 Peak and Subsequent Decline: Exploring external factors or changes in the my life during these periods could provide valuable insights.
Reasons for Skipping Songs: Investigating the types of songs skipped or the context in which I skipped could reveal more about my taste and listening habits.
Platform Preference: Using Android as the primary platform we could inform platform-specific optimizations or recommendations.
Diverse Catalog: I have explored a wide range of music, with 989 unique artists, 2134 unique songs, and 1936 unique albums. This suggests a broad taste in music.
Original Spotify Dataset:

Date and time of when the stream ended in UTC format (Coordinated Universal Time zone).

Your Spotify username.

Platform used when streaming the track (e.g. Android OS, Google Chromecast).

For how many milliseconds the track was played.

Country code of the country where the stream was played.
IP address used when streaming the track.
User agent used when streaming the track (e.g. a browser, like Mozilla Firefox, or Safari).
Name of the track.
Name of the artist, band or podcast.
Name of the album of the track.
A Spotify Track URI, that is identifying the unique music track.
Name of the episode of the podcast.
Name of the show of the podcast.
A Spotify Episode URI, that is identifying the unique podcast episode.
Reason why the track started (e.g. previous track finished or you picked it from the playlist).
Reason why the track ended (e.g. the track finished playing or you hit the next button).
Whether shuffle mode was used when playing the track.
Information whether the user skipped to the next song.
Information whether the track was played in offline mode.
Timestamp of when offline mode was used, if it was used.
Information whether the track was played during a private session.

But after data cleaning ,data preprocessing and removing redundant data:undefinedReason End :

![dataset_cleaned](https://github.com/user-attachments/assets/2b7d59db-677a-45c9-82b2-0096381cd241)

“trackdone” - The track played to its end

“fwdbtn” - The user pressed Next/Forward

“endplay” - The user started playing something else (by clicking a track or Play/Shuffle buttonor similar)

“backbtn” - The user pressed Back

“logout” - The app was shut down or theuser logged out. “remote” - The track playback was moved to another device.

“unexpected-exit” - The app was shut down eitherby the user, or by the operating system, or it crashed.

“unexpected-exit-while-paused” - Theplayback was paused, and at some point after that, the app was shut down either by the user,or by the operating system, or it crashed.

“trackerror” - The playback of theprevious track ran into some form of error, and this was the next track to play

“remote” - The track playback was moved to another device

“clickrow” - The userpressed a specific track in a list of tracks.

Part of Day:

Data model:
![model](https://github.com/user-attachments/assets/02c3c863-86de-47b4-a36c-1f8c34eef07c)

undefined

Additional project images


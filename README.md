# YouTube-Songs-Data-Analysis
This notebook contains an analysis of YouTube songs data, including views, likes, comments, and publishing trends. The dataset includes information such as video IDs, channel titles, song titles, descriptions, tags, view counts, like counts, comment counts, and more.

Dataset

The dataset is loaded from an Excel file named songs.xlsx and contains 19,345 entries with 14 columns. The columns include:

video_id: Unique identifier for each video

channelTitle: Name of the YouTube channel

title: Title of the video

description: Video description

tags: Tags associated with the video

publishedAt: Date and time of publication

viewCount: Number of views

likeCount: Number of likes

favoriteCount: Number of favorites

commentCount: Number of comments

duration: Duration of the video

definition: Video definition (e.g., HD)

caption: Whether the video has captions

song_name: Extracted song name from the title

Data Cleaning
Handling Missing Values: The dataset had 3 missing values in the description column, which were dropped.

Extracting Song Names: The song_name column was created by extracting the main song name from the title column.

Analysis

Top 5 Songs by View Count

The top 5 songs with the highest view counts were identified and visualized using a bar chart.

Top 5 Songs by Like Count

The top 5 songs with the highest like counts were identified and visualized using a bar chart.

Top 5 Songs by Comment Count

The top 5 songs with the highest comment counts were identified.

Visualizations

The notebook includes bar charts to visualize the top songs by view count and like count, providing a clear comparison of the most popular songs based on these metrics.

Conclusion

This analysis provides insights into the popularity of songs on YouTube based on views, likes, and comments. The visualizations help in understanding which songs perform best in terms of engagement.


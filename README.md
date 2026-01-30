# 🎵 Spotify Music Analysis

## 📚 About data
This is a dataset of Spotify tracks over a range of 125 different genres. Each track has some audio features associated with it including, but not limited to, danceability, energy, key, loudness, mode, tempo, speechiness, and more. 

The data is in CSV format which is tabular and can be loaded quickly. The dataset has already been formatted and ready-to-use. Only minor changes had to be made to better fit the objectives of this analysis. 

The dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset).

## ❔ Question
**What Drives Music Popularity?**
1. Which audio features correlates most with popularity
2. How does explicit content relate to popularity
3. Do shorter songs perform better?

## 🔍 Analysis
1. How do audio features (tempo, loudness, etc.) relate to track popularity, and does this relationship differ for explicit vs. non-explicit songs?

**Danceability vs. Popularity**

Danceability shows a positive relationship with popularity for both groups. The relationship is stronger for explicit tracks, suggesting different musical elements such as tempo, rhythm stability, beat strength, and overall regularity plays a larger role in popularity for explicit content. Non-explicit content might rely more on lyricism or simpler beats rather than stronger dancing elements. 


**Liveness vs. Popularity**

Liveness shows little to no relationship with popularity for non-explicit tracks, while a weak negative relationship is observed for explicit tracks. This is expected, as the majority of music in the dataset is studio-recorded rather than captured in live performance settings. Overall, both studio-recorded and live tracks can achieve similar popularity levels. However, the downward trend among explicit tracks suggests that higher liveness values are less common among highly popular explicit songs, indicating that popular explicit content is more often studio-produced than live-recorded.

**Instrumentalness vs. Popularity**

Instrumentalness shows a negative relationship with popularity for both explicit and non-explicit tracks. This indicates that tracks with fewer or no vocals tend to be less popular, while vocal-driven songs generally achieve higher popularity. The relationship is more pronounced among explicit tracks, suggesting that highly popular explicit music is particularly reliant on vocal presence rather than instrumental-only composition.

**Valence vs. Popularity**

Valence shows little to no relationship with popularity for non-explicit tracks, while a weak positive relationship is observed for explicit tracks. This suggests that the popularity of non-explicit songs is largely independent of musical positivity, relying instead on other factors. For explicit tracks, the small positive trend indicates that higher valence (happier or more positive-sounding music) is slightly associated with increased popularity.


**Tempo vs. Popularity**

Tempo shows little to no relationship with popularity for non-explicit tracks, while a weak positive relationship is observed for explicit tracks. This suggests that the popularity of non-explicit songs is largely independent of the beats per minute (tempo), relying instead on other factors. For explicit tracks, the small positive trend indicates that faster tempo is slightly associated with increased popularity.

2. Do shorter songs perform better?
   
**Duration vs. Popularity**

Duration shows a strong negative relationship with popularity for both explicit and non-explicit tracks. The average track length is about 3.87 minutes, and songs longer than this tend to be DJ mixes, non-English tracks, or ambient music for studying/sleeping. This suggests that shorter, standard-length tracks are generally more popular across all groups.

## 📊 Visualization
Produced a story analysis walking through some highlights of the data.

Tableau: [Story](https://public.tableau.com/app/profile/ana.garcia2226/viz/SpotifyMusicAnalysis_17697329880890/SpotifyAudioAnalysis)

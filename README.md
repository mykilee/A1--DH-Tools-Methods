# A1--DH-Tools-Methods
assignment 1 for DH: Tools and Methods 

# Spotify Songs

The data this week comes from Spotify via the [`spotifyr` package](https://www.rcharlie.com/spotifyr/). [Charlie Thompson](https://twitter.com/_RCharlie), [Josiah Parry](https://twitter.com/JosiahParry), Donal Phipps, and Tom Wolff authored this package to make it easier to get either your own data or general metadata arounds songs from Spotify's API. Make sure to check out the [`spotifyr` package](https://www.rcharlie.com/spotifyr/) website to see how you can collect your own data!

[Kaylin Pavlik](https://twitter.com/kaylinquest/status/1213138536570015745) had a recent [blogpost](https://www.kaylinpavlik.com/classifying-songs-genres/) using the audio features to explore and classify songs. She used the `spotifyr` package to collect about 5000 songs from 6 main categories (EDM, Latin, Pop, R&B, Rap, & Rock). 

h/t to [Jon Harmon](https://github.com/rfordatascience/tidytuesday/issues/160) & [Neal Grantham](https://twitter.com/nsgrantham/status/1213190975113199616).


### Data Dictionary

# `spotify_songs.csv`

|variable                 |class     |description |
|:---|:---|:-----------|
|track_id                 |character | Song unique ID|
|track_name               |character | Song Name|
|track_artist             |character | Song Artist|
|track_popularity         |double    | Song Popularity (0-100) where higher is better |
|track_album_id           |character | Album unique ID|
|track_album_name         |character | Song album name |
|track_album_release_date |character | Date when album released |
|playlist_name            |character | Name of playlist |
|playlist_id              |character | Playlist ID|
|playlist_genre           |character | Playlist genre |
|playlist_subgenre        |character | Playlist subgenre|
|danceability             |double    | Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable. |
|energy                   |double    | Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy. |
|key                      |double    | The estimated overall key of the track. Integers map to pitches using standard Pitch Class notation . E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1. |
|loudness                 |double    | The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typical range between -60 and 0 db.|
|mode                     |double    | Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.|
|speechiness              |double    | Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks. |
|acousticness             |double    | A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.|
|instrumentalness         |double    | Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0. |
|liveness                 |double    | Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live. |
|valence                  |double    | A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry). |
|tempo                    |double    | The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration. |
|duration_ms              |double    | Duration of song in milliseconds |

# Research Project

This repository is dedicated to a research project focused on [The influence of music genres on people's emotions.]. The aim is to [provide insights into mental health: Understanding how different music genres influence emotions can offer insights into mental health and well-being. This could be crucial for developing music therapy or mental health intervention measures.].


## Topic selection 

For the upcoming weeks, the chosen topic for exploration is [Does different genres of music, such as pop, classical, and rock, have varying effects on an individual's overall mood?].

## Context

1.Rucsanda, M. (2015). The effect of various music genres on the adolescents’ emotional state. Bulletin of the Transilvania University of Braşov, Series VIII: Performing Arts, 8(2-Suppl.), 167-176.

2.Stulov, I. H. (2019). THE IMPACT OF MUSIC ON PEOPLE'S FEELINGS AND EMOTIONS. In Академическая наука-проблемы и достижения (pp. 34-42).

3.Burger, B., Saarikallio, S., Luck, G., Thompson, M. R., & Toiviainen, P. (2012, July). Emotions move us: Basic emotions in music influence people’s movement to music. In Proceedings of the 12th international conference on music perception and cognition and 8th triennial conference of the european society for the cognitive sciences of music (pp. 177-182). Thessaloniki, Greece: Aristotle University of Thessaloniki.

4.Bugdol, M. N., Bugdol, M. D., & Smreczak, T. (2018). The influence of music genres on human emotionality. In Innovations in Biomedical Engineering (pp. 107-114). Springer International Publishing.

## Research Question (RQ) and/or Hypothesis

**Research Question:**
[Does different genres of music, such as pop, classical, and rock, have varying effects on an individual's overall mood?]

**Hypothesis:**
[Different types of music, such as pop, classical, and rock, significantly impact individuals' overall emotions in distinct ways.]

## Exploration and Methods

To explore the proposed topic and address the research questions, the following methods and tools will be considered:

- Method 1: [Cultural and Demographic Analysis:Consider the influence of cultural and demographic factors on emotional responses to different music types;Stratify participants based on cultural background, age, or other relevant demographics for subgroup analysis.]
- Method 2: [Content Analysis:Perform content analysis of the lyrics, rhythm, and other musical elements to identify potential contributors to emotional responses;Relate the content analysis findings to participants' reported emotions.]

## Data Requirements

To answer the research questions and test the hypothesis, the following types of data will be needed:

- Data Type 1: [Describe Data Type 1]
- Data Type 2: [Describe Data Type 2]

## Tools and Methods

Potential tools and methods that could be used include:

- Tool 1: [Mention Tool 1, if applicable]
- Methodology: [Mention Methodology, if applicable]


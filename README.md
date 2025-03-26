# Creating-Cohorts-of-Songs_ML_Clustering_Algorithm

Project: Spotify Song Cohort Analysis
Problem Scenario
In today's digital age, customers expect personalized experiences. Whether it's tailored recommendations on e-commerce platforms or curated content on streaming services like Netflix, users seek information that aligns with their individual preferences. To maintain and enhance customer engagement, companies must consistently deliver the most relevant content.

This project focuses on Spotify, a leading audio streaming and media service provider. With over 456 million monthly active users, including more than 195 million paid subscribers (as of September 2022), Spotify aims to improve its song recommendation system. The company's goal is to create "cohorts" of songs with similar characteristics. By grouping songs based on relevant features, Spotify can provide more accurate and personalized recommendations to its users.

Problem Objective
To perform exploratory data analysis (EDA) and cluster analysis to create these song cohorts. The primary objective is to gain a deeper understanding of the various factors that define song similarity and how these factors can be used to effectively group songs.

Data Description
The dataset comprises information obtained from Spotify's API, containing details about all albums by The Rolling Stones available on Spotify.

Key Data Characteristics:

Each song is uniquely identified.

Variables:

Variable

Description

name
The name of the song.

album
The name of the album.

release_date
The day, month, and year the album was released.

track_number
The order the song appears on the album.

id
The Spotify ID for the song.

uri
The Spotify URI for the song.

acousticness
A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.  Range: 0.0 (least acoustic) to 1.0 (most acoustic)

danceability
Describes how suitable a track is for dancing based on a combination of musical elements, including tempo, rhythm stability, beat strength, and overall regularity. 0.0 is least danceable, and 1.0 is most danceable.  Range: 0.0 (least danceable) to 1.0 (most danceable)

energy
A measure from 0.0 to 1.0 that represents the perceptual intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.  Range: 0.0 (least energetic) to 1.0 (most energetic)

instrumentalness
Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater the likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.






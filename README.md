# AVDB-4RC - Audio/Video Database for Rainfall Classification
The dataset AVDB-4RC (Audio/Video Database for Rainfall Classification) contains digital audio/video sequences recorded for seven different levels of precipitation intensity (see Table below).
In particular, the database presents a set of audio sequences containing the acoustic timbre produced by the rain and video sequences containing rain videos, both in seven different intensities.


|Rain Classification            | Precipitation Intensity     |
|-------------------------------|-----------------------------|
|NR – No rain                   | < 0.5 mm/h                  |
|W - Weak rain                   | [0.5 - 2] mm/h              |
|M - Moderate rain                   | [2 - 6] mm/h                |
|H - Heavy rain                   | [6 - 10] mm/h               |
|VH - Very Heavy rain                   | [10 - 18] mm/h              |
|S - Shower rain                   | [18 - 30] 0.5 mm/h          |
|C - Cloudburst rain                   | > 30 mm/h                   |




## Dataset Composition

The dataset is composed of:
* 10 audio-video files for the categories "No rain", "Weak rain", "Moderate rain", "Heavy rain" and "Very heavy rain";
* 3 audio-video files for the "Shower" category;
* 2 audio-video files for the "Cloudburst" category.

70% of the audio and video files make up the learning dataset, the remaining 30% make up the testing dataset.
Consequently, the learning dataset is divided into training dataset (70%) and validation dataset (30%).



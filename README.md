# Predicting Spotify Track Popularity (2022)

Can a Spotify track’s audio features predict, with at least 75% accuracy, the track’s popularity on Spotify?

## Technologies
- Python
- Numpy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn

## Implementation

This project uses a series of machine learning algorithms to predict the popularity of a song on Spotify using its audio features.

### Spotify Song Audio Features

* Important Audio Features: From [Spotify API](https://developer.spotify.com/documentation/web-api/reference/#/)

* **id** *string*:
  * the Spotify ID for the track. release_date string: the date the album was first released.
popularity integer: the popularity of the track. The value will be between 0 and 100, with 100 being the most popular. The popularity is based, in the most part, on the total number of plays the track has had and how recent those plays are.

* **acousticness** *number*:
  * a confidence measure from 0.0 to 1.0 of whether the track is acoustic.

* **danceability** *number*:
  * describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.

* **duration_ms** *integer*:
  * the duration of the track in milliseconds.

* **energy** *number*:
  * a measure from 0.0 to 1.0 that represents a perceptual measure of intensity and activity.

* **instrumentalness** *number*:
  * predicts whether a track contains no vocals. The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks.

* **key** *integer*:
  * the key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.

* **liveness** *number*:
  * detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.

* **loudness** *number*:
  * the overall loudness of a track in decibels (dB). Values typically range between -60 and 0 db.

* **mode** *integer*:
  * indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.

* **speechiness** *number*:
  * detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value.

* **tempo** *number*:
  * the overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.

* **time_signature** *integer*:
  * an estimated time signature. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure). The time signature ranges from 3 to 7 indicating time signatures of "3/4", to "7/4".

* **valence** *number*:
  * a measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).




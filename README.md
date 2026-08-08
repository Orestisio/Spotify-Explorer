 Spotify Data Reference

A compact summary of Spotify's official **Understanding your data** documentation.

> The exact fields available depend on the data package and what applies to your account.

Source: Spotify Support — [Understanding your data](https://support.spotify.com/nl-en/article/understanding-your-data/)

## At a glance

| Data category | What it contains | 
|---|---|---|
| **Playlist** | Playlists, songs, artists, albums/episodes, descriptions, followers | 
| **Your Library** | Saved songs, episodes, shows, artists, albums and Spotify URIs | Snapshot at request |
| **Inferences** | Market segments inferred from interests/preferences | Current data |
| **Taste Profiles** | Personalized taste summaries, related Spotify URIs, notes, timestamps | Generated profile data |
| **Wrapped Data** | Annual listening stats, top artists/tracks/genres/podcasts and Wrapped stories | Latest Wrapped year |
| **Streaming History** | Stream end time, creator, title and `msPlayed` | Past year |
| **Extended Streaming History** | Detailed listening activity plus playback, device, location and technical fields |
## Details
---

## 1. Playlist

Spotify describes **Playlist** data as a summary of playlists you created or
saved, including saved songs.

### Included data

* Playlist name
* Date the playlist was last modified
* Names of songs in the playlist
* Names of artists for each song
* Names of albums or podcast episodes
* Local track name, when locally saved audio was uploaded for Spotify playback
* Playlist descriptions added by the user
* Number of followers of the playlist

---

## 2. Your Library

**Your Library** is a snapshot of the content saved in your library at the time
you requested your data.

### Included data

* Entity names
* Album and show names
* Creators
* Item Spotify URIs (Uniform Resource Identifiers)

The library can include saved:

* Songs
* Episodes
* Shows
* Artists
* Albums

---

## 3. Inferences

Spotify states that it draws certain **inferences about your interests and
preferences** from your use of Spotify and from data obtained from advertisers
and other advertising partners.

### Included data

* A list of market segments with which you are currently associated

Depending on your settings, these inferences may be used to provide
interest-based advertising within Spotify.

---

## 4. Taste Profiles

The **Taste Profiles** file contains personalized summaries of your streaming
taste and listening patterns.

### Included data

* Personalized summaries of streaming taste and patterns
* Spotify identifiers (URIs) for associated artists
* Spotify identifiers (URIs) for associated podcast episodes
* Spotify identifiers (URIs) for associated audiobooks
* Notes you have provided
* Timestamps showing when the data was generated

---

## 5. Wrapped Data

Spotify's **Wrapped data** contains your latest Wrapped data, when Wrapped is
available in your market.

### Included data, where available

* Number of unique artists listened to during the year
* Top artists
* Milliseconds spent listening to the #1 artist
* Top percentage of fans for the top artist
* Number of genres listened to
* Top genres
* Top podcasts
* Milliseconds spent listening to the top podcast
* Top percentage of fans for the top podcast
* Total milliseconds spent listening to podcasts
* Top tracks
* Number of plays for the top track
* First date the top track was played during the year
* Total distinct tracks played
* Total milliseconds listened on Spotify
* Day with the most listening time
* Minutes of content listened to on the top listening day
* Top percentage of worldwide listeners
* One-off Wrapped stories for that year

---

## 6. Streaming History

Spotify provides two related concepts: **Streaming History** and
**Extended Streaming History**.

### 6.1 Streaming History

The standard **Streaming History** covers audio, video, and podcasts listened
to or watched during the **past year**.

### Included data

* Date and time the stream ended, in UTC
* Creator of the streamed item (for example, artist name)
* Name/title of the item
* `msPlayed` — the number of milliseconds the item was played

---

## Quick comparison

| Data category              | Main purpose                         | Time scope             |
| -------------------------- | ------------------------------------ | ---------------------- |
| Playlist                   | Playlists and their contents         | Current/account data   |
| Your Library               | Saved Spotify content                | Snapshot at request    |
| Inferences                 | Interest and preference segments     | Current data           |
| Taste Profiles             | Personalized taste summaries         | Generated profile data |
| Wrapped Data               | Annual listening summary             | Latest Wrapped year    |
| Streaming History          | Listening/watching activity          | Past year              |
| Extended Streaming History | Detailed listening/watching activity | Account lifetime       |

---

## Important distinction

For analyzing listening behavior, the most useful distinction is:

**Streaming History**
→ relatively compact activity data for the past year.

**Taste Profiles**
→ Spotify's personalized interpretation/summary of listening taste.

**Inferences**
→ Spotify's inferred interests/preferences and associated market segments.

**Wrapped Data**
→ Spotify's annual summary and statistics.

**Your Library / Playlist**
→ what you have explicitly saved or organized.

---

## Source

Spotify Support. **Understanding your data**.
https://support.spotify.com/nl-en/article/understanding-your-data/


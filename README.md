# Song Class

In this lab, we'll be dealing with a `Song` class. The `Song` class can produce individual songs, each with a name, an artist, and a genre. We also want our `Song` class to be able to keep track of various statistics such as the number of songs created, the list of artists, the list of genres, the count of songs per genre, and the count of songs per artist.

## Usage

### Initialization
```python
from song import Song

# Create a Song object
ninety_nine_problems = Song("99 Problems", "Jay-Z", "Rap")

# Accessing attributes of a song
print(ninety_nine_problems.name)    # Output: "99 Problems"
print(ninety_nine_problems.artist)  # Output: "Jay-Z"
print(ninety_nine_problems.genre)   # Output: "Rap"
# Accessing class-level attributes
print(Song.count)            # Output: 0 (initial count)
print(Song.genres)           # Output: [] (initial empty list)
print(Song.artists)          # Output: [] (initial empty list)
print(Song.genre_count)      # Output: {} (initial empty dictionary)
print(Song.artist_count)     # Output: {} (initial empty dictionary)

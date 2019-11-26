# Music Relabeler

## About
Uses count-vectorizer and cosine similarity to locate the best matching album folder in your directory to modify.
Then pairs up local filenames to the online tracklist using the same strategy to rename them.

## Usage
1. Run notebook from music folder directory.
1. Copy the Wikipedia URL for a music album.
1. Pase URL into prompt.
1. Enjoy the results!

## Troubleshooting
If an assertion error occurs, the tracklistings do not match.
This is likely due to bonus tracks and/or missing tracks.
Another reason can be tracks with different names due to new releases.
Manually drop/rename the culprit rows from the tracklist dataframe.
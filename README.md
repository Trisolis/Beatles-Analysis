# Beatles-Analysis
A Jupyter notebook project that covers The Beatles, their songs, and how their career is viewed pre and post-Rubber Soul.

## Setup
1. git clone ...
2. cd project
3. python -m venv venv
4. source venv/Scripts/activate
5. pip install -r requirements.txt
6. Run jupyter notebook in console to access properly, or use through whatever IDE you want to
Run!

## Dataset
This dataset was compiled manually from multiple sources. No single existing dataset contained all the variables needed for this analysis. Below are the columns which need further explanation or sourcing:
- Songs, albums, and dates are all taken from the [Beatles Albums Discography](https://en.wikipedia.org/wiki/The_Beatles_albums_discography) and [Beatles Singles Discography](https://en.wikipedia.org/wiki/The_Beatles_singles_discography) pages on Wikipedia. I chose to use only official UK albums and singles, excluding their non-Beatles work and the latter half of *Yellow Submarine* (which was not written or performed by them)
- Duration was sourced from a [Kaggle dataset](https://www.kaggle.com/datasets/devedzic/the-beatles-songs-dataset)
- Songwriter/lead vocalist takes data from [Music Graffiti](https://www.music-graffiti.com/beatles_songs.htm), which goes into detail on who wrote and performed what specifically. All compositions officially are written by Lennon-McCartney (and sometimes Harrison/Starr), but this is more of an accurate look at who wrote and sang each. Of course, there will be some uncertainty, but this is the best I could find
- Rankings include [UME's Top 50](https://ultimateclassicrock.com/beatles-top-50/), [Rolling Stone's Top 100](https://www.rollingstone.com/music/music-lists/100-greatest-beatles-songs-154008/), [NME's Full Ranking](https://www.nme.com/features/the-beatles-every-song-ranked-3121214), and [USA Today's Full Ranking](https://ftw.usatoday.com/story/entertainment/pop-culture/2023/11/02/beatles-greatest-songs-every-ranked-sgt-pepper-50th-anniversary/81914346007/) 
- RYM and AOTY scores are from [The Beatles' RYM page](https://rateyourmusic.com/artist/the-beatles) and [AOTY page](https://www.albumoftheyear.org/artist/2523-the-beatles/) respectively
- Spotify streams sourced from [kworb](https://kworb.net/spotify/artist/3WrFJ7ztbogyGnTHbHJFl2_songs.html)

Not all columns are used, but I still think it's interesting and useful to have the full information on the whole dataset
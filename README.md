# python-music-downloader
Python script for downloading Deezer playlist music from Youtube

### Description
This script will download a Deezer playlist songs from Youtube and save it as MP3 file. MP3 files will be saved under "Download" folder and Playlist file will also be created under the script root directory.

### Credits
This script is based on yask123's Instant-Music-Downloader Python script. All credit goes to him.
https://github.com/yask123/Instant-Music-Downloader

### Usage
Audio Format:
python deezermusic -mp3 -playlist <Deezer_playlist_id>
OR for multple playlists
python deezermusic -mp3 -playlist <Deezer_playlist_id_1> <Deezer_playlist_id_2>

Video Format:
python deezermusic -mp4 -playlist <Deezer_playlist_id>
OR for multple playlists
python deezermusic -mp4 -playlist <Deezer_playlist_id_1> <Deezer_playlist_id_2>

Note: no playlist file will be created for Video files.




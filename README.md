# python-music-downloader
Python script for downloading Deezer playlist music from Youtube

### Description
This script will download a Deezer playlist songs from Youtube and save it as MP3 file. MP3 files will be saved under "Download" folder and Playlist file will also be created under the script root directory.

### Credits
This script is based on yask123's Instant-Music-Downloader Python script. All credit goes to him.
https://github.com/yask123/Instant-Music-Downloader

### Usage
####Audio Format:
```python deezermusic -mp3 -playlist <Deezer_playlist_id>```

####Video Format:
```python deezermusic -mp4 -playlist <Deezer_playlist_id>```

No playlist file will be created for Video files.


## Installation
WIP


### Note:
You would also need `libav` to download in `.mp3` format.

#### On Mac Os X
##### Installation by [Brew](https://brew.sh)
```bash
 $ brew install libav
 ```
 
#### On Ubuntu 

```bash
 $ sudo apt-get install libav-tools 
```
#### On Windows
>[See this](https://github.com/yask123/Instant-Music-Downloader/issues/19) 



## Disclaimer

Downloading copyrighted material may be illegal in your country. Use at your own risk.


## The MIT License
> Copyright (c) 2015 Yask Srivastava http://iyask.me

> Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.




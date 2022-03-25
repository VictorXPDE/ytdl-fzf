# ytdl-fzf 
A simple script for downloading videos from YouTube, Twitter, Reddit and other websites with a Fuzzy Finder.

#### Dependencies:

* [yt-dlp](https://github.com/yt-dlp/yt-dlp)
* [fzf](https://github.com/junegunn/fzf)

#### Installation:
Clone the project's repository and give the script execution permissions.
```
$ git clone https://github.com/VictorXPDE/ytdl-fzf
$ cd ytdl-fzf
$ chmod +x ytdl-fzf
```
Now move the script to `/usr/local/bin` or any other directory in your `$PATH`
```
$ sudo mv ytdl-fzf /usr/local/bin
```

#### Usage:
```
ytdl-fzf <format> <url>
```
Where `<format>` would be:

* `a` for audio.
* `v` for video.
* `a+v` or `v+a` for audio and video together.

Example:
```
$ ytdl-fzf a+v https://www.youtube.com/watch?v=Wb3UrJjAac4
```

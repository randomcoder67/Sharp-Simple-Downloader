# Sharp Simple Downloader

An easy to use TUI interface for downloading videos with [yt-dlp](https://github.com/yt-dlp/yt-dlp/).  
Written in C# using [Spectre.Console](https://spectreconsole.net/), runs on Windows, MacOS and Linux.  

Designed to be easy to use for new yt-dlp users, and for people who don't like/aren't familiar with using the command line.

## Features

* 

## Usage



## Dependancies

* yt-dlp
* .NET

### Linux

#### Arch Linux

`sudo pacman -S yt-dlp dotnet-runtime dotnet-sdk`

**This section will be updated more as I test on more systems**

## Installation

``` sh
git clone URL
cd Sharp-Simple-Downloader
make full
```

## Roadmap

### Target Feature for 1.0

* Quality selection
* Codec selection (H264/AVC, VP9, AV1, M4A, Opus)
* Audio only option
* Metadata options (thumbnails, metadata, chapters, all)
* --download-archive functionality
* Ordered filenames, keep consistent when playlist edited
* Alternative downloaders (aria2c)
* Download progress
* Pause and resume download
* Queue up downloads
	* Organise into folders

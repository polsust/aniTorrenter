# aniTorrenter
CLI website scraper for anime written in python

Keep in mind that since this uses torrent technology it will only work with animes or chapters that are being seeded at the current moment  

This means you probably won't be able to download the one piece episode 345

aniTorrenter will only show the torrents that have current seeders

# Usage

```bash
aniTorrenter one piece 
```

# Installation 

## Dependencies

```bash
pip install pyfzf beautifulsoup4
npm install -g webtorrent
```

* [**aria2**](https://github.com/aria2/aria2) - as a torrent downloader
* [**fzf**](https://github.com/junegunn/fzf) - to select the desired torrent through the terminal
* [**mpv**](https://github.com/mpv-player/mpv) - as a video player

## aniTorrenter

**curl** aniTorrenter to /usr/local/bin/

And give it execute permissions

```bash
sudo curl -sL "https://raw.githubusercontent.com/PolSust/aniTorrenter/main/aniTorrenter" -o /usr/local/bin/aniTorrenter
sudo chmod +x /usr/local/bin/aniTorrenter
```

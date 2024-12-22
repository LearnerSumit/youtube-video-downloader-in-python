# YouTube Video Downloader with Audio (MP4 Format)

This Python script allows you to download YouTube videos in MP4 format with both video and audio merged. It uses the powerful [yt-dlp](https://github.com/yt-dlp/yt-dlp) library, which is a fork of youtube-dl, for enhanced downloading capabilities.

## Features

- Downloads YouTube videos in **MP4 format**.
- Combines **video and audio** into a single file.
- Ensures high-quality video up to 1080p (or best available below 1080p).
- Avoids downloading playlists; only downloads a single video.

## Requirements

Before running the script, ensure the following are installed:

1. **Python** (version 3.6 or later)
2. **yt-dlp**:
   Install yt-dlp using pip:
   ```bash
   pip install -U yt-dlp

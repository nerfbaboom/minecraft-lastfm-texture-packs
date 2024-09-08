# Minecraft Texture Replacer with Last.fm Album Covers

This script replaces Minecraft block textures in a resource pack with the album covers from your Last.fm top albums. It uses dominant color comparison to match block textures with the closest album cover, resizing each image to fit Minecraft's requirements.

## Features
- Fetches top albums from a Last.fm user profile.
- Downloads album covers and stores them locally.
- Compares the dominant color of block textures with album covers to find the closest match.
- Replaces Minecraft block textures with the matched album covers.
- Ensures textures are resized to at least 64x64 pixels.

## Requirements

### Python Libraries
- `requests`
- `PIL` (Pillow)
- `colorthief`
- `concurrent.futures`

### Install dependencies
You can install the required libraries by running:
```bash
pip install requests pillow colorthief

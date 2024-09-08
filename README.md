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

Last.fm API Key

You will need a Last.fm API key to fetch the top albums. You can get an API key by signing up for a Last.fm account and registering for API access here.

Once you have your API key, add it to the script.
Usage

    Clone the repository:

    bash

git clone https://github.com/yourusername/minecraft-texture-replacer.git
cd minecraft-texture-replacer

Set your Last.fm credentials: In the script, update the API_KEY and USER variables with your Last.fm API key and username.

Run the program:

bash

    python script.py

    The script will:
        Fetch top albums from your Last.fm profile.
        Download album covers.
        Replace Minecraft block textures with album covers that have the closest matching dominant color.

    Minecraft Resource Pack Folder: Make sure your Minecraft resource pack is set up properly in the texture_folder directory, pointing to your textures/block folder.

Example

If your Last.fm top albums include artists like Radiohead, The Beatles, and Kendrick Lamar, their album covers will be downloaded and mapped onto the Minecraft block textures (e.g., cobblestone, dirt, and sand).
License

This project is licensed under the MIT License. See the LICENSE file for details.
Contributing

Feel free to submit issues or pull requests if you have any suggestions or improvements!

markdown


### How to Use:
- Replace the `yourusername` in the `git clone` URL with your GitHub username.
- Update the `script.py` filename if you decide to change the name of the main Python script file.

This `README.md` will guide users on how to install, configure, and run your script easily. Let me know if you want any changes or additions!

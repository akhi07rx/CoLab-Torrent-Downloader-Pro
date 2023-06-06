![maintenance-status](https://img.shields.io/badge/maintenance-actively--developed-brightgreen.svg)

# CoLab-Torrent-Downloader-Pro

This code allows you to download torrents directly to your Google Drive using Google Colab.

## Features

- Download torrents from magnet links
- Save downloaded files to a specified location on Google Drive
- Display a progress bar and information about the downloaded file
- Prompt the user to enter the magnet link or exit
- Handle incorrect inputs and display error messages

## Prerequisites

- A Google account with access to Google Drive and Google Colab
- A magnet link for the torrent you want to download

- Python 3.x
- libtorrent

## Installation

1. Install the required libraries by running `!pip install libtorrent-python google-colab`.

2. Mount your Google Drive by running `from google.colab import drive; drive.mount('/content/drive')` and following the instructions.

3. Set the `save_path` variable in the script to the desired location on your Google Drive where you want to save the downloaded files.

## How to Use

1. Run the script.

2. Select an option from the main menu:

   - Enter Magnet link: Enter a magnet link to download a torrent.
   - Upload Torrent file: Upload a torrent file to download a torrent.
   - File Options: View file details such as "File Name," "Extension," "File Size," and "File Link" (which displays the downloaded magnet link).
   - Exit: Exit the program.

3. If you selected "Enter Magnet link" or "Upload Torrent file," follow the prompts to enter a magnet link or upload a torrent file.

4. The script will start downloading the torrent and display a progress bar.

5. After the download is complete, you can view file details by selecting "File Options" from the main menu.

6. When you are finished, select "Exit" from the main menu to exit the program.

## Code Components

The code consists of several components:

- Importing necessary libraries: `libtorrent`, `time`, `re`, `os`, `pickle`, `google.colab.drive`, `google.colab.files`, and `tqdm`.
- Mounting Google Drive and setting up session parameters.
- Defining regular expression pattern for validating magnet links.
- Loading resume data from previous sessions.
- Displaying main menu and handling user input.
- Downloading torrents using magnet links or torrent files.
- Displaying progress bar while downloading.
- Saving resume data for future sessions.
- Displaying file options menu and showing file details.

## Acknowledgments

This project was inspired by various open-source torrent downloader projects.

This code was developed with the help of online resources and examples. Special thanks to the developers of the `libtorrent`, `google.colab`, and `tqdm` libraries for their contributions.

## License

This project is licensed under the MIT License.

## Disclaimer

Please note that downloading and sharing copyrighted material without permission is illegal in many countries. Make sure you have the right to download and share the content before using this code.

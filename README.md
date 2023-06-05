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

## How to Use

1. Open the code in Google Colab.
2. Run the first cell to install the `libtorrent` library and mount your Google Drive.
3. When prompted, enter the magnet link of the torrent you want to download or 'exit' to quit.
4. If you enter an invalid magnet link, the code will display an error message and prompt you to try again.
5. The code will download the torrent and display a progress bar and information about the downloaded file.

## Code Components

- `libtorrent`: A library for downloading and uploading torrents
- `google.colab.drive`: A module for mounting Google Drive in Google Colab
- `tqdm`: A library for displaying progress bars

## Acknowledgments

This code was developed with the help of online resources and examples. Special thanks to the developers of the `libtorrent`, `google.colab`, and `tqdm` libraries for their contributions.

## License

This code is released under the MIT License. See the LICENSE file for more information.

## Disclaimer

Please note that downloading and sharing copyrighted material without permission is illegal in many countries. Make sure you have the right to download and share the content before using this code.

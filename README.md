# Youtube-Playlist-Downloader-using-python
## YouTube Playlist Downloader
## Description
This is a simple YouTube playlist downloader application built using PyQt5 and pytube. The application allows users to enter a YouTube playlist URL, load the playlist, and download selected videos from the playlist to a specified location. It utilizes multi-threading to handle playlist loading and video downloads in the background, ensuring a responsive user interface.

## Requirements
Python 3.x
PyQt5
pytube
## Install the required packages using the following command:
pip install PyQt5 pytube

# Usage
## Run the script by executing the following command:
python youtube_downloader.py

### The application window will appear.
Enter a valid YouTube playlist URL in the provided input field.
Click the "Load Playlist" button to load the playlist information into the table.
Optionally, select videos for download by checking the corresponding checkboxes in the "Download" column.
Click the "Select All" button to select all videos, or manually select individual videos.
Click the "Download Selected" button to choose a download location and start downloading the selected videos.
A progress dialog will be displayed, showing the progress of video downloads.
## Features
### Load Playlist: Loads the videos from the specified YouTube playlist.
### Select All: Selects all videos in the playlist for download.
### Download Selected: Downloads the selected videos to a specified location.
### Download Progress: Displays download progress using a progress dialog.
### Error Handling: Handles errors during playlist loading and video downloading, displaying error messages.
## Styling
The application features a simple and clean user interface with styling applied using QSS (Qt Style Sheets). The styling enhances the visual appeal of the application.

## Notes
Make sure to provide a valid YouTube playlist URL for accurate results.
The application uses the pytube library to interact with YouTube and download videos.
## License
This application is provided under the MIT License. See the LICENSE file for details.
# Screanshots:
![Screenshot 2023-12-23 164710](https://github.com/Mahaning/Youtube-Playlist-Downloader-using-python/assets/92427624/40fbe2e0-3c1a-4a4b-8a1e-ecf314644a1b)


![Screenshot 2023-12-23 164631](https://github.com/Mahaning/Youtube-Playlist-Downloader-using-python/assets/92427624/9042ab6e-eb31-4b1d-b6db-f9ba1f12e2ca)

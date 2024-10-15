## Pexels Image and Video Downloader

This project is a Python script that uses the Pexels API to automatically download images and videos based on a search query. The script allows you to specify the number of images and videos to download, resize images, and display them.



## Features:
	•	Download Images: You can download images based on any search query (e.g., “mountains,” “forest”).
	•	Download Videos: You can download videos related to the search query.
	•	Resize Images: The script can resize images after downloading.
	•	Display Images: It includes functionality to display the images in the Jupyter Notebook using matplotlib.


## Prerequisites:
	1.	Python 3.x
	2.	The following Python libraries must be installed:
	•	requests
	•	Pillow
	•	matplotlib

##  Setup:
1.	Get your Pexels API Key:
	•	Sign up for the Pexels API and generate your API key.
	2.	Clone the repository:
	•	Clone the GitHub repository to your local machine.
	3.	Add your API Key:
	•	In the script, replace the placeholder API key with your own Pexels API key:

## How to Use:
## Download Images:
To download images based on a search query (e.g., “mountains”), use the download_images function: download_images("mountains", num_images=10) This will download 10 images of mountains and save them to the pexels_images folder.

## Download Videos:
To download videos based on a search query (e.g., “nature”), use the download_videos function:
download_videos("nature", num_videos=5) This will download 5 videos of nature and save them to the pexels_videos folder.

## Example Queries:
You can modify the search term to download different types of images and videos, such as:
	•	"city"
	•	"ocean"
	•	"forest"
	•	"mountain"

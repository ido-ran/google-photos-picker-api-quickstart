# Google Photos Picker API Quick Start Python

Small example of how to use Python3 to access Google Photos Picker API to download user-selected photos and videos.

This quick start was created by following the instructions of [Google Photos Picker API Getting Starter](https://developers.google.com/photos/picker/guides/get-started-picker).

## How to run?

1. Follow the Getting Started instructions of how to enabled Google Pohotos Picker API in Cloud Console
2. Follow [Google API Client Quickstart](https://developers.google.com/docs/api/quickstart/python) to create OAuth client id and download `credentials.json` file to this folder
3. Create Python virtual-env using `python3 -m venv venv`
4. Activate it using `source venv/bin/activate`
5. Install dependecies using `python -m pip install -r requirements.txt`
6. Run `python quickstart.py` and open the `pickerUri` in a browser, selecte the photos and videos and come back to the python console.
7. The files will be downloaded to the current folder


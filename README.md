# Subscriptions from NewPipe to YouTube

This Python project allows users to automate subscribing to YouTube channels via the YouTube Data API v3. It reads a list of channels from a JSON file and automatically subscribes to them using a Google Colab environment.

## Features
* Authenticate with the YouTube API using OAuth 2.0.
* Read YouTube channel URLs from a subscriptions.json file.
* Automatically subscribe to the listed channels.
* Handles duplicate subscriptions and provides error handling.

## Prerequisites
Before running the script, ensure you have:

### Google Cloud Project:

* Enable the YouTube Data API v3.
* Create OAuth 2.0 credentials and download the client_secret.json file.

### Google Colab Environment:

* The code is designed to run in Google Colab.
* You can upload the necessary files directly into the notebook.  

Required Files:

* client_secret.json: OAuth credentials from Google Cloud Console.  
* subscriptions.json: A file that contains the YouTube channel URLs you want to subscribe to.  

Example format:
``` json
{
  "subscriptions": [
    {"url": "https://www.youtube.com/channel/CHANNEL_ID_1"},
    {"url": "https://www.youtube.com/channel/CHANNEL_ID_2"}
  ]
}
```
## How to Use
* Clone the Repository:  
First, clone the repository to your local machine:  
  ```bash
  git clone https://github.com/deepanshumidha5140/Newpipe-To-Youtube
  cd youtube-subscription-manager
  ```
* Google Cloud Setup:  
Go to Google Cloud Console.  
Enable YouTube Data API v3.  
Create OAuth credentials and download the client_secret.json file.  
* Run the Script in Google Colab:
Open a Google Colab notebook.  
Upload the client_secret.json and subscriptions.json files when prompted.  
* Execute the Code:
Run the provided code in Colab.  
You will be asked to authenticate using Google OAuth.

### Demo
https://github.com/user-attachments/assets/d65b6489-6a47-4edc-8b06-a6e5b0acac48

### Youtube API Charts
![Screenshot 2024-10-20 144701](https://github.com/user-attachments/assets/fe0f2965-7d1b-4150-b13e-d18cca9a404f)
![Screenshot 2024-10-20 144729](https://github.com/user-attachments/assets/1ba29a29-bbce-44e4-b644-d47fc6d9702f)
![Screenshot 2024-10-20 144818](https://github.com/user-attachments/assets/e6f76f59-85ec-47c1-bcd3-9a4e2c96223d)

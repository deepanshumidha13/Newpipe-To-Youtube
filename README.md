# YouTube Subscription Manager

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
  git clone https://github.com/yourusername/youtube-subscription-manager.git
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
https://github.com/user-attachments/assets/a51bdfab-58b8-488a-8d19-ae2240017a45

### Youtube API Charts
![Screenshot 2024-10-20 144701](https://github.com/user-attachments/assets/45657abb-d052-4a5a-911a-8a46c977350b)
![Screenshot 2024-10-20 144729](https://github.com/user-attachments/assets/b0da72e0-6b00-4c24-8d6f-7658f80dfc2b)
![Screenshot 2024-10-20 144756](https://github.com/user-attachments/assets/cccb3ae3-ac9b-42f2-8ab0-e67f1625b001)
![Screenshot 2024-10-20 144818](https://github.com/user-attachments/assets/33ff96b2-60d3-4b25-a941-f693c1600008)

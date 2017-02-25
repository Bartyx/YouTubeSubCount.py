# YouTubeSubCount.py

I have only tested this on the latest version of Rasbian.

**Instructions**
Download the script. Edit the CHANNEL_ID, YOUTUBE_DATA_API_V3, and YOUR CHANNEL portions. Then run with root.

Like this for example:
```
wget https://raw.githubusercontent.com/dee-oh-double-gee/YouTubeSubCount.py/master/YouTubeSubCount.py

sudo nano YouTubeSubCount.py 
```
Edit the CHANNEL_ID, YOUTUBE_DATA_API_V3, and YOUR CHANNEL parts of the script to your channel ID (cannot be the channel name, must be the full ID), then paste in your youtube data API key, and then you can edit the print line to say whatever you want. CTRL+x to close and save.
```
sudo python YouTubeSubCount.py
```
The script will update every 5 seconds. My channel is small so I only have it update every minute but by default it refreshes every 5 seconds. 

This is my first python script so please help me out and make changes that could improve the script.

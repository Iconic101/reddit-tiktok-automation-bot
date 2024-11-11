# reddit-video-maker
makes TikTok style videos based on reddit posts and comments automatically 

## Setup:

Download all files

create files `bg_vids` and `exports` in main directory

add background videos in mp4 or mov format to bg_vids, make sure they're inv `1080 x 1920` aspect ratio
add any background music in wav or mp3 format to the `music` folder

Open main directory

 - `cd reddit-video-maker`

Install dependencies

 - `pip3 install moviepy praw PIL pyttsx3`

Change the PRAW token information of redditScrape.py in both the `longForm/utils` and `askreddit/utils` folders

 - get all the stuff you need https://github.com/reddit-archive/reddit/wiki/OAuth2-Quick-Start-Example#first-steps
``` 
reddit = praw.Reddit (
    client_id="yourClientID",
    client_secret="yourClientSecret",
    user_agent="<yourUserAgent>"
) 
```

(if you struggle with this step go here: https://praw.readthedocs.io/en/stable/getting_started/quick_start.html)

run main.py from either longform or askreddit while still in main directory

 - `python3 longForm/main.py` or `python3 askreddit/main.py`
#   r e d d i t - t i k t o k - a u t o m a t i o n - b o t  
 
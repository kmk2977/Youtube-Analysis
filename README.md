# Youtube-Analysis

![](https://www.mygrow.me/wp-content/uploads/2020/03/302-3020719_youtube-music-logo-png-transparent-background-youtube-logo.jpg)
![](https://upload.wikimedia.org/wikipedia/commons/7/77/2018_Linus_Tech_Tips_logo.svg)

YouTube Data API - [LINK](https://developers.google.com/youtube/v3/getting-started)

## Aims & Objectives
1.Getting to know Youtube API and how to obtain video data.
2.Analyzing video data and verify different common "myths" about what makes a video do well on Youtube, for example:
  -Does the number of likes and comments matter for a video to get more views?
  -Does the video duration matter for views and interaction (likes/ comments)?
  -Does title length matter for views?
  -How many tags do good performing videos have? What are the common tags among these videos?
  -Across all the creators I take into consideration, how often do they upload new videos? On which days in the week?
3.Explore the trending topics using NLP techniques
  -Which popular topics are being covered in the videos (e.g. using wordcloud for video titles)?
  -Which questions are being asked in the comment sections in the videos

## Youtube Channel Description 
![video](https://user-images.githubusercontent.com/55085437/174777812-74f8dd0d-8d14-4e1c-b326-3f3ca1bca5ba.png)

## Step-1

Go to the Google Developer's Console [link](https://console.cloud.google.com/apis/dashboard?pli=1&project=new-project-351811) to obtain the credentials.

## Step-2

Create a new Project. ![screen1](https://user-images.githubusercontent.com/55085437/174775094-961bcfcc-a031-4935-b8c3-5025e63f20dd.png)

## Step-3

We need the API key which we will be obtaining from the newly created Project. Copy the newly generated API credentials and store it into a variable into ur python variable say api_key. ![screen2](https://user-images.githubusercontent.com/55085437/174775193-c36c72b1-9669-41a5-acbd-975f31d5a887.png)

## Step-4

Enable the API service, Click on the ![screen3](https://user-images.githubusercontent.com/55085437/174775876-708fbf27-f987-4a37-b17e-7bebdc5aac78.png) in the dashboard section then search for the "youtube data v3", click on it and hit Enable.



Rest you can refere to the python notebook attached for the code.

For channel name I picked [LinusTechTips](https://www.youtube.com/c/LinusTechTips) cause i really like their content.

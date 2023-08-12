# Exploratory Data Analysing Using Youtube Video Data from Most Popular Data Science Channels

The scope of this small project is limited to data science channels and I will not consider other niches (that might have a different characteristics and audience base). Therefore, in this project will explore the statistics of around 10 most successful data science Youtube channel.

## 1. Aims, objectives and background

Within this project, I would like to explore the following: <br>
<br>
• Getting to know Youtube API and how to obtain video data. <br>
• Analyzing video data and verify different common "myths" about what makes a video do well on Youtube, for example:<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Does the number of likes and comments matter for a video to get more views?<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Does the video duration matter for views and interaction (likes/ comments)?<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Does title length matter for views?<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• How many tags do good performing videos have? What are the common tags among these videos?<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Across all the creators I take into consideration, how often do they upload new videos? On which days in the week?<br>
  • Explore the trending topics using NLP techniques.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Which popular topics are being covered in the videos (e.g. using wordcloud for video titles)?<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Which questions are being asked in the comment sections in the videos<br>


  ## 2. Steps of the project
  
  Obtain video meta data via Youtube API for the top 20-30 channels in the data science niche, this includes several small steps: <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Create a developer key, request data and transform the responses into a usable data format.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Prepocess data and engineer additional features for analysis.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Exploratory data analysis.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Bulding a tableau dashboard.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Conclusions.<br>

  ## 3. Dataset
  
  **• Data selection :** As this project is particularly focused on data science channels, I found that not many readily available datasets 
  online are suitable for this purpose. I created my own dataset using the Google Youtube Data API version 3.0. The exact steps of data 
  creation is presented below.

  **• Data limitations :** The dataset is a real-world dataset and suitable for the research. However, the selection of the top 10 Youtube 
  channels to include in the research is purely based on my knowledge of the channels in data science field and might not be accurate. My 
  definition is "popular" is only based on subscriber count but there are other metrics that could be taken into consideration as well 
  (e.g. views, engagement). The top 10 also seems arbitrary given the plethora of channels on Youtube. There might be smaller channels that 
  might also very interesting to look into, which could be the next step of this project.

  **• Ethics of data source:** According to Youtube API's guide, the usage of Youtube API is free of charge given that your application send 
   requests within a quota limit. "The YouTube Data API uses a quota to ensure that developers use the service as intended and do not 
   create applications that unfairly reduce service quality or limit access for others. " The default quota allocation for each application 
   is 10,000 units per day, and you could request additional quota by completing a form to YouTube API Services if you reach the quota 
   limit.

  Since all data requested from Youtube API is public data (which everyone on the Internet can see on Youtube), there is no particular 
  privacy issues as far as I am concerned. In addition, the data is obtained only for research purposes in this case and not for any 
  commercial interests.


## 4. Conclusions and future research ideas

In this project, we have explored the video data of the 28 most popular Data science/ Data analyst channels and revealed many interesting findings for anyone who are starting out with a Youtube channel in data science or another topic:

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• The more likes and comments a video has, the more views the video gets (it is not guaranteed that this is a causal relationship, it is &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;simply a correlation and can work both way). Likes seem to be a better indicator for interaction than comments and the number of &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;likes seem to follow the "social proof", which means the more views the video has, the more people will like it.<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Most videos have between 5 and 30 tags.<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Most-viewed videos tend to have average title length of 6-12 words. Too short or too long titles seem to harm viewership.<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• There is a small variation in the number of video uploads on weekdays.<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Comments on videos are generally positive, we noticed a lot "please" words, suggesting potential market gaps in content that could be &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;filled.

**4.1. Project limitation:**

 The findings should also be taken with a grain of salt for a number of reasons:

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• The number of videos is quite small (the dataset has only ~5,779 videos)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• There are many other factors that haven't been taken into the analysis, including the marketing strategy of the creators and many &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;random effects that would affect how successful a video is

**4.2. Ideas for future research:**

To expand and build on this research project, one can:

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Expand the dataset to also smaller channels in data science niche

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Do sentiment analysis on the comments and find out which videos get more positive comments and which videos get less positive &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;comments

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Do market research by analyzing questions in the comment threads and identifying common questions/ market gaps which could &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;potentially filled

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Conduct this research for other niches (e.g. vlogs or beauty channels), to compare different niches with each other to see the different &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;patterns in viewership and video characteristics.

## 5. References/ Resources used:
[1] Youtube API. Avaiable at https://developers.google.com/youtube/v3

[2] Thu Vu Repository: https://github.com/thu-vu92/youtube-api-analysis/tree/main

[3] Tina Haung Repository: https://github.com/thu-vu92/youtube-api-analysis/tree/main

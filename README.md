# Exploratory Data Analysing Using Youtube Video Data from Most Popular Data Science Channels

The scope of this small project is limited to data science channels and I will not consider other niches (that might have a different characteristics and audience base). Therefore, in this project will explore the statistics of around 10 most successful data science Youtube channel.

## 1.1 Aims, objectives and background

Within this project, I would like to explore the following: <br>
• Getting to know Youtube API and how to obtain video data. <br>
• Analyzing video data and verify different common "myths" about what makes a video do well on Youtube, for example:<br>
  • Does the number of likes and comments matter for a video to get more views?<br>
  • Does the video duration matter for views and interaction (likes/ comments)?<br>
  • Does title length matter for views?<br>
  • How many tags do good performing videos have? What are the common tags among these videos?<br>
  • Across all the creators I take into consideration, how often do they upload new videos? On which days in the week?<br>
  • Explore the trending topics using NLP techniques.<br>
  • Which popular topics are being covered in the videos (e.g. using wordcloud for video titles)?<br>
  • Which questions are being asked in the comment sections in the videos<br>


  ## 1.2 Steps of the project
  
  • Obtain video meta data via Youtube API for the top 20-30 channels in the data science niche (this includes several small steps: <br>
    • create a developer key, request data and transform the responses into a usable data format)<br>
    • Prepocess data and engineer additional features for analysis<br>
  • Exploratory data analysis.<br>
  • Bulding a tableau dashboard.<br>
  • Conclusions.<br>

  ## 1.4 Dataset
  
  **Data selection :** As this project is particularly focused on data science channels, I found that not many readily available datasets 
  online are suitable for this purpose. I created my own dataset using the Google Youtube Data API version 3.0. The exact steps of data 
  creation is presented in section 2. Data Creation below.

  **Data limitations :** The dataset is a real-world dataset and suitable for the research. However, the selection of the top 10 Youtube 
  channels to include in the research is purely based on my knowledge of the channels in data science field and might not be accurate. My 
  definition is "popular" is only based on subscriber count but there are other metrics that could be taken into consideration as well 
  (e.g. views, engagement). The top 10 also seems arbitrary given the plethora of channels on Youtube. There might be smaller channels that 
  might also very interesting to look into, which could be the next step of this project.

  **Ethics of data source:** According to Youtube API's guide, the usage of Youtube API is free of charge given that your application send 
   requests within a quota limit. "The YouTube Data API uses a quota to ensure that developers use the service as intended and do not 
   create applications that unfairly reduce service quality or limit access for others. " The default quota allocation for each application 
   is 10,000 units per day, and you could request additional quota by completing a form to YouTube API Services if you reach the quota 
   limit.

  Since all data requested from Youtube API is public data (which everyone on the Internet can see on Youtube), there is no particular 
  privacy issues as far as I am concerned. In addition, the data is obtained only for research purposes in this case and not for any 
  commercial interests.

# Azure-Media-Services-Football-Sentiment-Analysis-Podcast

The notebook is an attempt to determine if a podcast focusing on a specific football team (PSG) is positive or negative. For doing so, I used Azure Media Services.

# Step 1 Transform the podcast via Azure Media Services

From the Azure Portal, I created a Media Services account and use the wizard to create a job.
Basically, I define the following:
* The podcast URL
* What I want to do? In my case, it was an audio analyzer. https://docs.microsoft.com/en-us/azure/media-services/latest/analyze-video-audio-files-concept
* What language to use? The podcast is in French so I chose French. However, the service is able to detect the language

As the result, the service creates a couple of files that require some exploration for extracting some insights

# Step 2 Apply some transformations and explore the results
The files created are raw data. A few transformations were required to achieve what I wanted to do.
I created jupiter notebook for this purpose.

# Step 3 Validate the approach
Response in the notebook :)

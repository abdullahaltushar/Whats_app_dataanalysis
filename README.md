# Whats app data analysis

# *Introduction*:

Whatsapp has quickly become the world’s most popular text and voice messaging application. Specializing in cross-platform messaging with over 1.5 billion monthly active users, this makes it the most popular mobile messenger app worldwide.

- I thought of various projects on which I could analyse data like - *Air Quality Index* or The *cliched* *Covid-19 Data Analysis*.

- But I thought why not do **Data Analysis on a WhatsApp group chat** of *college students* and find out interesting insights about *who is most active, who are ghosts (the ones who do not reply), my sleep schedule,* *the most used emoji, the most actives times of the day, or does the group use phones during college teaching hours?* 

- These would be some interesting insights for sure, more for me than for you, since the people in this chat are people I know personally.

# *Data Retrieval & Preprocessing*
### Beginning. How do I export my conversations? From Where To Obtain Data?

<p align="center">
</p>

- The first step is **Data Retrieval & Preprocessing**, that is to **gather the data**. WhatsApp allows you to **export your chats** through a **.txt format**. 

- Go to the respective chat, which you want to export!

<p align="center">
<img src="assets/extras/whatsapp-options.jpg" width=150 align="center">
</p>

- Tap on **options**, click on **More**, and **Export Chat.**

<p align="center">
<img src="assets/extras/whatsapp-export-chat.jpg" width=150>
</p>

- I will be Exporting **Without Media.**

<p align="center">
<img src="assets/extras/whatsapp-media.jpg " width=200 length=150 align="center">
</p>

#### NOTE:
- Without media: exports about **40k messages **
- With media: exports about *10k messages along with pictures/videos* 
- While exporting data, *avoid including media files* because if the number of media files is greater than certain figure then not all the media files are exported.

### Opening this .txt file up, you get messages in a format that looks like this:

<img src="assets/extras/textfile.png" align="center">


# *Exploratory Data Analysis*

At this point, I think I’m ready to start my analysis so I will plot a simple line graph to see the frequency of messages over the months. 

## The overall frequency of total messages on the group

I expect to see a nice line graph with crests and troughs in odd places.

<p align="center">
<img src="assets/codes/import.PNG">
</p>
<p align="center">
<img src="assets/plot/plot.PNG">
</p>



### Result

<p align="center">
<img src="assets/codes/Capture.PNG">
</p>
<p align="center">
<img src="assets/codes/outputs.PNG">
</p>

# *Conclusion*

**That’s it from my end! I hope you learned and enjoyed a lot!**

<p align="center">
<img src="assets/extras/5-the-office.gif">
</p>

It’s really interesting to see the texting habits of people and incidents of daily life reflected in the text. I suggest you take a look at my code and apply it to your own group chats. However, some modifications will have to be done at the DataFrame creation part. 

If you’re interested, shoot me a message and I’ll help you out.

- Extending this Whatsapp Analysis Project!
    - Adding a **Sentiment Analyser to the texts** — *Swear Words & Sentiments*!
    - Libraries called `profanity_check`, `TextBlob`, `VADER` (Valence Aware Dictionary and Sentiment Reasoner) from NTLK and TextBlob.

- Instagram Data Analysis
- Play Store Data Analysis
- Exploring more datasets! It is never-ending, as there can be **Infinite Stories with Data**!
- Once, done with enough Data Analysis, try making Datasets, scraping Data from websites and creating Interesting Datasets!

> And the best time to do it is right now, today, because tomorrow, typically means never.


***Thank you for reading!***

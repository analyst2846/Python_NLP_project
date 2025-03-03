# Python_NLP_project
Trump political campaign analysis using text mining techniques.

In this project , I analysed Trump's 2017 to 2020 political campaign.
The data contains transcripts from his 103 rallies ( the transcripts capture all his speech as well as crowd reactions).

My business case was to work for the democratic party and try to gather information about how Trump represent them as well as mainly Joe Biden.


1) I did named entity recognition to see the most talked about democratic leaders refereed to by Trump during his speech.
2) I took the prominent democratic leaders identified and tried to see the frequency of their mentions among all transcripts ( there was a significant increase in mentions towards 2020).
3) I did a cosine similarity measure among transcripts and concluded that Trump kind of switches gears towards the end ( near 2020) in his discourse and went full on attack mode on his opponents.
   I would recommend the democratic party to review one of the last transcripts as they are the most representative.
4) I then analyzed the crowd reactions ( they are in brackets in the transcript), as they represent the voters that we want to influence. I used regex pattern to isolate the crowd reactions and the preceding phrase ( that triggered the reaction). I did sentiment analysis to create 2 classes ( positive and negative), then tried PMI and chi-sqaure information extraction to represent the most discriminative words between the 2 classes.
5) At the end , I did topic modeling on Joe Biden using BERTTopic and NMF ( having a small dataset of Joe Biden phrases)


### Topic modeling for a Spanish song

This repo provides an application of NLP tools in a corpus extracted from the lyrics rap Spanish song named Manifiesto by Nach

###Pipeline
**1. **Requested the endpoint
**2. **Retrieve lyrics from the HTML using BeutifulSoup and a bit clean
**3.** Translate lyrics using googletrans API
**4**. tag and lemmatize these words furthermore remove stop words and punctuation
**5.** Create a dictionary toker-id pair and filter words with a frequency lower than some threshold
**6.** Implement TfidfModel() class to normalize 
**7. **And finally, use gensim.models.LdaMulticore() class to perform topic modeling

###Dependencies
- Requests
- Nltk
- Pandas
- Googletrans
- BeautifulSoup
- Gensim

### Topic modeling for a Spanish song

This repo provides an application of NLP tools in a corpus extracted from the lyrics rap Spanish song named Manifiesto by Nach

### Pipeline

<ol>
<li>Requested the endpoint</li>
<li>Retrieve lyrics from the HTML using BeutifulSoup and a bit clean </li>
<li>ranslate lyrics using googletrans API </li>
<li> tag and lemmatize these words furthermore remove stop words and punctuation </li>
<li>Create a dictionary toker-id pair and filter words with a frequency lower than some threshold </li>
<li>Implement TfidfModel() class to normalize </li>
<li>And finally, use gensim.models.LdaMulticore() class to perform topic modeling </li>
</ol>

### Dependencies
- Requests
- Nltk
- Pandas
- Googletrans
- BeautifulSoup
- Gensim

### Results
Due to the song talks about one topic essentially, the returned topics presents quite similarities between them

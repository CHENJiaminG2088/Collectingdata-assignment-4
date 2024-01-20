## A brief description of the corpus

### 1.The description of the corpus:
This corpus comes from(https://www.kaggle.com/datasets/rikdifos/rap-lyrics) and contains the rap lyrics of 36 rappers. The data includes artist names and their rap lyrics but no song titles.


### 2.The target audience and the intended use of the corpus:
This dataset/corpus may be helpful to people who want to study what their favorite rappers are singing about, or who want to perform sentiment analysis on rap lyrics.


### 3.Text selection criteria.
There is a certain degree of richness, completeness, and no garbled characters.


### 4.The data collection process.
I found several interesting data sets on the website kaggle, and then compared the data sets in terms of richness, whether they were pre-cleaned, etc., until I found a data set that I thought was more suitable for analysis.


### 5.Cleaning and/or preprocessing steps.
When processing the lyrics data in the Rap Lyrics folder, the following cleaning and preprocessing steps were performed:  
1. **Tokenization:** - Split the lyrics of each song into words.
2. **Lemmatization:** - Lemmatize each word, converting it to its base form to reduce vocabulary diversity.
3. **Part-of-Speech Tagging:** - Label each word with its part of speech, such as noun, verb, adjective, etc. 4.
4. **Proper Noun Extraction:** - Identify and extract proper nouns in lyrics, such as names of people, places, etc., to reveal key elements in songs. 
5. **Named Entity Recognition:** - Identify named entities in lyrics.
6. **Data Merging:** - Merge artist metadata and lyric data to create a more comprehensive dataset.


### 6.The format of the files in the corpus:
the format of all files in the corpus are txt.

### 8.The description of the columns in the CSV file.
|  Header name | description |
| ------------- | ------------- |
| filename  | rapper's name |
| text | lyrics |
| DOC | spaCy document object, which contains the results of tagging, word segmentation, part-of-speech tagging, etc. on the original text. |
| Tokens | Split the smallest unit of text |
| Lemmas | the basic form of the word, processed by lemmatization |
| Pos| Grammatical categories of lexical units, such as nouns, verbs, adjectives|
| Proper_Nouns | Proper nouns identified in the text|
| named_entities | Words that represent specific things in text, such as names of people, places, organizations, etc.|
| NE_words | Named entity vocabulary extracted from lyric text, where named entities are vocabulary units with special meanings in the text|



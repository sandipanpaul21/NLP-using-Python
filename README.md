## NLP-using-Python

Welcome to a Natural Language Processing series, using the Natural Language Toolkit, or NLTK, module with Python

### 01 Tokenizing Word and Sentence 
#### Token
  * Each "entity" that is a part of whatever was split up based on rules. 
  * For examples, each word is a token when a sentence is "tokenized" into words.
  * Each sentence can also be a token, if you tokenized the sentences out of a paragraph.

### 02 Stop Words
 * Stop words as words that just contain no meaning, we want to remove them.
 * Words like we, she, is, a etc.

### 03 Stemming
 * The idea of stemming is a sort of normalizing method.
 * Many variations of words carry the same meaning, other than when tense is involved.
 * The reason why we stem is to shorten the lookup, and normalize sentences.

### 04 POS & Chunking
 * Part of Speech (POS)
  1. This means labeling words in a sentence as nouns,adjectives,verbs...etc. 
 * Chunking
  1. Group words into hopefully meaningful chunks.
  2. One of the main goals of chunking is to group into what are known as "noun phrases." 
  3. These are phrases of one or more words that contain a noun, maybe some descriptive words

### 05 Named Entity Recognition
 * The idea is to have the machine immediately be able to pull out "entities" 
 * like people, places, things, locations, monetary figures, and more.
 * There are two major options with NLTK's named entity recognition: 
  1. Either recognize all named entities
  2. Or recognize named entities as their respective type, like people, places, locations, etc.

# HASOC-2020

## Participated in Hate Speech and Offensive Content Identification in Indo-European Languages (HASOC) 2020 Challenge! by Team name - NSIT_ML_Geeks (Roushan Raj & Shivangi Srivastava)

Competition tasks discription - https://hasocfire.github.io/hasoc/2020/

### Our Model's Ranks in this Competition :  
    
  - Hindi Sub-task A : 1st
  - Hindi Sub-task B : 2nd
  
  - German Sub-task A : 18th
  - German Sub-task B : 14th
  
  - English Sub-task A : 32th
  - English Sub-task B : 16th
  
## Instructions : 
- Training data and Testing data are provided here : https://github.com/roushan-raj/HASOC-2020/tree/master/Dataset
- Rankings (Leaderboard of HASOC FIRE 2020) can be found here : https://github.com/roushan-raj/HASOC-2020/tree/master/Leaderboard
- Trained model for English : https://github.com/roushan-raj/HASOC-2020/tree/master/Models/English%20Models
- Trained model for Hindi : https://github.com/roushan-raj/HASOC-2020/tree/master/Models/German%20Models
- Trained model for German : https://github.com/roushan-raj/HASOC-2020/tree/master/Models/Hindi%20Models
- The Word-Embeddings used in our models can be downloaded from below :
    - GloVe : https://nlp.stanford.edu/projects/glove/
    - FastText : https://fasttext.cc/docs/en/crawl-vectors.html
- Results of all three language models evaluated on test data : https://github.com/roushan-raj/HASOC-2020/tree/master/Results

## Tasks
There are two sub-tasks in each of the languages. Below is a brief description of each task.

### Sub-task A: Identifying Hate, offensive and profane content

This task focus on Hate speech and Offensive language identification offered for English, German, and Hindi. Sub-task A is coarse-grained binary classification in which participating system are required to classify tweets into two classes, namely: Hate and Offensive (HOF) and Non- Hate and offensive (NOT).

- (NOT) Non Hate-Offensive - This post does not contain any Hate speech, profane, offensive content.
- (HOF) Hate and Offensive - This post contains Hate, offensive, and profane content.

### Sub-task B: Discrimination between Hate, profane and offensive posts

This sub-task is a fine-grained classification offered for English, German, and Hindi. Hate-speech and offensive posts from the sub-task A are further classified into three categories:

- (HATE) Hate speech:- Posts under this class contain Hate speech content.
- (OFFN) Offenive:- Posts under this class contain offensive content.
- (PRFN) Profane:- These posts contain profane words.

### Categories Explanation:

HATE SPEECH: Describing negative attributes or deficiencies to groups of individuals because they are members of a group (e.g. all poor people are stupid). Hateful comment toward groups because of race, political opinion, sexual orientation, gender, social status, health condition or similar.

OFFENSIVE: Posts which are degrading, dehumanizing, insulting an individual, threatening with violent acts are categorized into OFFENSIVE category.

PROFANITY: Unacceptable language in the absence of insults and abuse. This typically concerns the usage of swearwords (Scheiße, Fuck etc.) and cursing (Zur Hölle! Verdammt! etc.) are categorized into this category.

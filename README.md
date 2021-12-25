# LING 380 Final Paper

In this repository resides the code for Question 2 of our project. All of the code, scratch work, and spreadsheets were processed using Jupyter Notebooks.

## Breakdown of Repository Contents
### ./averages/
Contains zipped numpy files of each word used to compute the average embedding vector in Question 2, by language.

### ./bert-base-multilingual-cased/
Contains the multilingual BERT model used to compute embeddings of words in Russian, Polish, Czech, German, and Finnish. Model is available at Hugging Face, but was omitted here for size concerns.

### ./german/
Contains data used for German analyses and the corpus of cased nouns. The notebook derives the nouns needed for our analysis from the larger corpora.

### ./graphics/
Graphics used in the paper.

### ./graphics_new/
More graphics used in the paper, but with updated correctness for their corresponding files in ./graphics/.

### ./Slavic-BERT-NER/
Contains the Slavic BERT model that we considered using, but ultimately did not. `Czech (from jacob).ipynb` is just my checking the metadata of the Czech file sent by Jacob. `Finnish cases.ipynb` contains the webscraper to get Finnish declensions. Likewise for `Russian webscraper.ipynb` and `Polish.ipynb.`

### final.ipynb
Has code passing strings through the multilingual BERT. Some of my early experimentation with PCA is also visible.

### Question 2 pickling.ipynb
By far the code that took the longest to run. Contains code to run every relevant declined noun through the multilingual BERT and save it in a numpy file.

### Question 2.ipynb
Contains some experimentation with the mean embedding vector and correlation. Also contains the least squares code used to compute results. Contains code to create visual graphics. Contains code for additional experiments and relevant visualizations.

### Spreadsheet analysis.ipynb
This file's title is quite literal. Code within was used to get data on spreadsheet data, mostly for the discussion section of Question 2.

### LING 380 Final Project Proposal.pdf
Where it all began...

### NLP_Final_Project_ (1).pdf
... and how it all culminated. Enjoy the paper, and Happy Holidays!




## Technology Opportunity Discovery using Naive Bayes and Natural  Lanugage Processing

[Click here to read the research paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0223404)

The following files are included with this project

1. Python Code in Jupyter Notebook
*NLP Project with Iphone Reviews.ipynb*

3. PDF printout of the above Jupyter Notebook
*NLP Project with Iphone Review.pdf*

3. Project Presentation as shown in class
*Final Project Presentation.pptx*

4. Dataset CSV
*review_iphone.csv*

Other csv files are generated during runtime:

1. `sent_key.csv` : Contains all the sentiment keywords with their TF-IDF data

2. `sentiments.csv` : Contains all the sentences with their predicted sentiment value from Naive Bayes classifier along with column that specifies is a sentiment keyword is present in the sentence.

3. `temp.csv` : Contains tokenised sentences with a word count.

4. `word.csv` : Contains all the words with their POS tags

5. `wrd2vec.csv` : Contains the result of the analysis. This has a list of all the opinion triggers and sentiment keywords that have a similarity matching above the threshold (defined in the notebook). The two columns are for model1 and model2. model1 is from CBOW word2vec and model2 is from skip-gram word2vec.

### Instructions to run the project

In order to run this project, you must have jupyter notebook installed in a Python 3 environment.

***List of Dependencies***
 - pip install numpy
 - pip install wordcloud 
 - pip install spacy 
 - pip install nltk 
 - pip install matplotlib 
 - pip install pandas 
 - pip install networkx
 - pip install gensim 
 - pip install sklearn 
 - pip install torch===1.5.0 torchvision===0.6.0 -f https://download.pytorch.org/whl/torch_stable.html 
 - pip install stanza

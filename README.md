# Topic Modelling
In machine learning and natural language processing, a topic model is a type of statistical model for discovering the abstract "topics" that occur in a collection of documents. Topic modeling is a frequently used text-mining tool for discovery of hidden semantic structures in a text body. 

Intuitively, given that a document is about a particular topic, one would expect particular words to appear in the document more or less frequently: "dog" and "bone" will appear more often in documents about dogs, "cat" and "meow" will appear in documents about cats, and "the" and "is" will appear equally in both. A document typically concerns multiple topics in different proportions; thus, in a document that is 10% about cats and 90% about dogs, there would probably be about 9 times more dog words than cat words. The "topics" produced by topic modeling techniques are clusters of similar words. A topic model captures this intuition in a mathematical framework, which allows examining a set of documents and discovering, based on the statistics of the words in each, what the topics might be and what each document's balance of topics is.

In this Jupyter notebook, two versions of [LDA (Latent Dirichlet Allocation)](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation) algorithm are used for topic modelling:
- [Gensim’s](https://radimrehurek.com/gensim/models/ldamodel.html) inbuilt version of the LDA algorithm.
- [Mallet's](https://radimrehurek.com/gensim/models/ldamallet.html) version of the LDA algorithm.

## Libraries Used
- [Gensim](https://radimrehurek.com/gensim/)
- [Spacy](https://spacy.io)
- [pyLDAvis](https://github.com/bmabey/pyLDAvis)
- [Numpy](http://www.numpy.org)
- [Pandas](https://pandas.pydata.org)
- [Matplotlib](https://matplotlib.org)

## How to run
- `git clone https://github.com/amanraj209/topic-modelling.git`.
- Install the required libraries using pip, virtual environment or conda.
- Run `jupyter notebook` in your terminal.
# TextClassification

![images](https://user-images.githubusercontent.com/68372273/182791238-77756982-8e5b-4f4d-bf2e-c1162c769bea.png)

## Target Audience:
Programmers who have interest in Natural Language Processing, or trying to learn how to classify folder texts within existing libraries.

## Objective: 
The aim of this project was to create a system that could read into files' texts, and classify texts based on the folder of the contained files. The project was a part of Natural Language Processing course.

## Tools:
In order to complete this project properly, I used "NLTK", "SKLearn", "re" and "pandas". Moreover:
* *NLTK*: To stem words and understand their roots. I've also used the "stop_words" from their corpus to remove any instances of stop words (e.g: of, in, at, on.. etc.)
* *SKLearn*: I used the "TfidfVectorizer" to vectorize words based on the metric "tf-idf" (Token Frequency - Inverse Document Frequency). In addition to PCA to perform dimensionality reduction and values shifting.
* *re*: Regular Expressions was used for further processing towards texts, such as removing unnecessary characters.
* *pandas*: It was used to create a dataframe to represent folders, files, and texts. Some used tools require a dataframe to process texts such as PCA and "TfidfVectorizer".

## Requirements:
* To run the code, you have to have any type of compiler that could run an ".ipynb" file, I strongly suggest Anaconda's "Jupyter Notebook" or "Microsoft Visual Code"
* For used tools, it's preferable if you use python version that's 3.7 or newer.
* After installing python, for tools installation, go to cmd, and write:
```
!pip install pandas
!pip install nltk
!pip install re
!pip install sklearn
```

## Dataset:
I've used Reuters dataset, which can be found [here](https://archive.ics.uci.edu/ml/datasets/reuters-21578+text+categorization+collection)!

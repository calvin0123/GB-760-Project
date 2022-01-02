# GB-760-Project

*This project was conducted by Calvin Chen, Daniel Hom, Duc Le, Lucius Liu, Vitchuda Poonyakanok, and Yuyang Xie in University of Wisconsin-Madison, Wisconsin School of Business in 2021*

## Intro
This project is about to build system to continuously read tweets from Twitter API to database and Kafka and scored phrases and words based on Twitter trends each minutes using Python and PostgreSQL


Watch our *[Demo Video!](https://www.youtube.com/watch?v=RsZ3ixB_C6Q)

## Milestone 1

* [**server.py**](server.py) - Read tweets from the Twitter API and write tweets to a .txt file

* [**word_count.py**](word_count.py) - Compute frequencies of words and phrases
```
python3 word_count.py -w -"input your word or phrase"
```

* [**vocabulary_size.py**](vocabulary_size.py) - Compute the number of unique words
```
python3 vocabulary_size.py
```

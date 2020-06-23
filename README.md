# About

This repo contains the code for publication analysis based on our bizpub.org journal dataset.

## Data

We collected the public data about the [50 Journals used in Financial Times Business School Research Ranking](https://www.ft.com/content/3405a512-5cbb-11e1-8f1f-00144feabdc0), including author information, title, keywords, subjects, and abstract.

 The sample data used in this repo includes the data for the following three journals (from the first issue to last issue by March 2020). The full dataset will be released in the near future.

- MIS Quarterly
- Information Systems Research
- Journal of Management Information Systems

`data/pub_raw.db`: this is the raw dataset we collected, which is then cleaned and processed for different analysis.

```
sqlite3 pub_raw.db .dump > pub_raw_mysql.sql
```
The database has the following tables:
<img width="183" alt="Screen Shot 2020-05-16 at 2 01 47 PM" src="https://user-images.githubusercontent.com/595772/82126916-dcd6eb00-977d-11ea-96b3-4af551040913.png">

## Setup

Python 3.6+ required, clone the repo, go to the repo folder, setup the virtual environment, and install the required packages:

```shell
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

Run `$ jupyter notebook` to go over the notebooks.

## Team

- [Harry Wang](http://harrywang.me/): Professor of Management Information Systems at the University of Delaware.
- [Eric Zhang](https://github.com/mianhu888): PhD student of Computer Science at the University of Delaware.

## Disclaimers

- The data we collected are all publicly displayed on journals' websites and the full texts of the publications are not provided.
- The dataset and related code are prepared for public research, teaching, and learning.

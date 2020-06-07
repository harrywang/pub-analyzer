# EDA

This folder performs EDA for sample dataset.

## Data

We collected the public data about the [50 Journals used in Financial Times Business School Research Ranking](https://www.ft.com/content/3405a512-5cbb-11e1-8f1f-00144feabdc0), including author information, title, keywords, subjects, and abstract.

The sample data used in this repo includes the data for the following three journals (from the first issue to last issue by March 2020). The full dataset will be released in the near future.

- MIS Quarterly
- Information Systems Research
- Journal of Management Information Systems

`data/pub_raw.db`: this is the raw dataset we collected, which is then cleaned and processed for different analysis. This is the sample dataset used for this EDA.


## Setup

Python 3.6+ required, clone the repo, go to the repo folder, setup the virtual environment, and install the required packages:

```shell
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

## Run the Notebook

Go to this folder and run `$ jupyter notebook` to go over the EDA.

```bash
$ cd eda
$ jupyter notebook
```


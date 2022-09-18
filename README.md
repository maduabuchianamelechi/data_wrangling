# data_wrangling
This project fetches data from different sources, identifies issues in the datasets during the wrangling process and cleans them up. Then gives a report of the wrangling process.

## The `wrangle_act`
This file contains the code for reading the datasets from diffenrent sources viz;

A `csv file`, imported using the `pandas` library.

A `tsv file`, imported from a url using the `request` library.

A tweet `json file`, imported from twitter API using the `tweepy` library.

It also contains the various steps taken to access the data both visually and programatically. The steps taken to wrangle and clean the dataset.

## The `wrangle_report`
This file contains the summary of all the processes in the `wrangle_act` notebook

## The `act_report`
This file contains a brief report of the findings made from the dataset.

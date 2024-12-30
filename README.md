# LongCovidSymptom_Classification_BERT
Paper title: Early Detection of Long COVID Symptoms from Social Media Using BERT. Author: Alfado Rafly Hermawan, Irmasari Hafidz, Rahmah Yasinta Rangkuti, Effi Latiffianti, Nur Aini Rakhmawati (Institut Teknologi Sepuluh Nopember Surabaya, Indonesia)

Presented at DASA 2024 **[https://dasa24.asu.edu.bh/conference-program/](https://dasa24.asu.edu.bh/conference-program/)**

## Dataset
The dataset is available via email and can be cite on Zenodo. How to cite the dataset: 
> Hafidz, I. (2024). Data_collection_longcovid_2022. Zenodo. https://doi.org/10.5281/zenodo.14227098

## Data Collection for my PhD Thesis
This dataset, containing 500K lines of tweet. related to #longcovid, was collected for symptom detection research. The ipynb is originally run from Deepnote account of the author. It was originally scraped using the Twitter API before restrictions forced actively on February 2023 (see Twitter API or https://developer.x.com/en/products/x-api ).
The dataset is accessible by email at irma@its.ac.id or ir.hafidz@gmail.com

## Data Acquisition Method
The dataset was compiled using the snscrape package, which allows scraping of tweets containing the term "longcovid" from a year 2022 period (e.g., January 1-31, 2022). The Python script loops through tweets in the specified month, extracting tweet content, IDs, usernames, and language. The scraping stops once 50,000 tweets are collected. The datetime library is used to record the end time of the process.

This code uses the snscrape package to scrape tweets about "longcovid" in English from each month for example January 1, 2022 to January 31, 2022.

The dataset was compiled using the snscrape Python package, which scrapes data from platforms like Twitter, Instagram, and Reddit. Specifically, I used the snscrape library (via sntwitter) to gather tweets containing "longcovid" from a defined period (e.g., January 1-31, 2022). The script loops through search results, collecting tweet data such as date, ID, content, username, and language, and stores them in a list (e.g., tweets_longcovid_jan_2022). The loop stops once 50,000 tweets are collected, and the datetime library records the end time of the scraping process.

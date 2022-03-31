# Disinformation-Dozen-TweetIDs

The repository contains an ongoing collection of tweets IDs associated with the coronavirus COVID-19 (SARS-CoV-2), we used Twitter’s streaming API to get all possible activities of two lists of users previously established: Disinformation Dozen and Good Information.

We obtained more than 700 thousand tweets divided according to the two categories and related to the activities (tweets, retweets, replies, quotes) and more than 7 million total retweets received.

We provide public access to this data in accordance with Twitter's terms of service, releasing tweet ids that can be used to retrieve full objects via the API.

## Data Organization
The structure of Tweet-IDs is as follows:
- Tweet-IDs are stored in folders indicating their origin (Disinformation Dozen or Good Information).
- Inside the respective folders we have two text files, one containing the Tweet-IDs of the activities performed (tweets, retweets, quotes, replies) and one of the retweets received.
- Activity-related tweets were collected from their date of subscription to Twitter until August 2021, retweets received were collected  in the period from September 2020 to August 2021 due to limitations imposed by the Twitter API.
- Tweets can be "hydrated" using [Hydrator](https://github.com/DocNow/hydrator), to do this just access the Hydrator github repository linked and follow the installation instructions in their README.

# Data Usage Agreement
This dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). By using this dataset, you agree to abide by the stipulations in the license, remain in compliance with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), and cite the following manuscript: 

Nogara G, Padinjaredath V, Cardoso F, Ayoub O, Giordano S and Luceri L.
The Disinformation Dozen: An Exploratory Analysis of Covid-19 Disinformation Proliferation on Twitter
WebSci22;
DOI:  
PMID: 

BibTeX:
```bibtex
@article{nogara2022disinformation,
  title={The Disinformation Dozen: An Exploratory Analysis of Covid-19 Disinformation Proliferation on Twitter},
  author={Gianluca Nogara, Padinjaredath Suresh Vishnuprasad, Felipe Cardoso, Omran Ayoub, Silvia Giordano and Luca Luceri},
  conference={WebSci22},
  year={2022}
}
```

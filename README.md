# Goodreads Book Ratings Forecasting

This repo contains my final capstone project for Springboard's Data Science Career Track certificate program. This project was a machine learning classification model used to forecast a reader's rating for a given book and a scale of 1-5.

**Python Libraries Used:**
In this project I utilized the following Python libraries:
* Pandas
* Numpy
* Seaborn (& Matplotlib)
* Sklearn
* nltk (for NLP & vader sentiment analysis)

## Raw Data

Data for this project was provided through the work of Mengting Wan and colleagues. See citations below to their papers and link to their website where the raw data can be found.

> *Citations:*
> 1. Mengting Wan and Julian McAuley. 2018. Item Recommendation on Mono- tonic Behavior Chains. In Twelfth ACM Conference on Recommender Systems (RecSys ’18), October 2–7, 2018, Vancouver, BC, Canada. ACM, New York, NY, USA, 9 pages. https://doi.org/10.1145/3240323.3240369
> 2. 2)	Mengting Wan, Rishabh Misra, Ndapa Nakashole, Julian McAuley, "Fine-Grained Spoiler Detection from Large-Scale Review Corpora", in ACL'19.
>
> [Goodreads Datasets](https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home)

The dataset contained millions of observations. The key sets used in my model were user ratings & text reviews along with book features, such as number of pages, author, year of publication, etc.

## Explanation of Model and Findings

For a in-depth explanation of the process I used for building this model, as well as a summary of findings and recommendations for action from the findings, please see the "Capstone_FinalReport" file in this repo.
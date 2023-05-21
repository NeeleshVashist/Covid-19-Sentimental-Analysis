# Covid-19 Sentiment Analysis using NLP

This project, Covid-19 Sentiment Analysis using NLP, is developed by the PyCoders team as a part of the NLP course in college. The team consists of the following members:

- Neelesh Vashist (Team Lead)
- Mukul Bisht
- Rohit Kumar
- Saurabh Singh

The project aims to perform sentiment analysis on Twitter data related to the Covid-19 pandemic. By analyzing the sentiment of tweets, we gain insights into people's emotions and public sentiment during the crisis.

## Abstract

This notebook presents novel results of Covid-19 sentiment analysis with concrete findings. We use off-the-shelf libraries with functional limitations, but overall results seem valid based on our analysis. For this project, we use NLTK, Vader, and TextBlob libraries for sentiment analysis.

## Introduction

The worldwide coronavirus pandemic has led to the establishment of curfews, quarantines, and lockdowns worldwide to mitigate the further spread of the virus. Understanding the public's responses to these changes can provide valuable insights. This study aims to answer the following questions:

1. How do people feel during the crisis?
2. How does the general public sentiment change over time?
3. What are the topics that most contribute to this sentiment shift?

We filtered the data to include tweets in English for ease of study. This section summarizes the results with a few graphs generated by the code in the latter section of the notebook.

## Installation

To run this project, follow these steps:

1. Download and install Anaconda, which includes Jupyter Notebook.
2. Fork and clone this repository.
3. Download the dataset from the following Google Drive link: [Covid-19 Sentiment Analysis Dataset](https://drive.google.com/drive/u/0/folders/1GdBYi2UqdFYRYy9E7JFgm8Z3tQjXVkED).
4. Move the downloaded dataset to the project directory/folder.

## Usage

1. Open the Jupyter Notebook by launching Anaconda and selecting the notebook file.
2. Run the notebook cells sequentially to execute the code.
3. Explore the results and visualizations generated by the sentiment analysis.

## Data

The data used in this project is extracted from Twitter. The dataset includes a collection of tweets related to the Covid-19 pandemic. By analyzing this data, we aim to gain insights into the sentiment of people during the crisis.

## Technologies

The following technologies and libraries are used in this project for sentiment analysis:

- NLTK
- Vader
- TextBlob

## What Could Be Improved

To enhance this project, the following improvements can be considered:

- Better sentiment analysis tool: Explore advanced models or approaches that account for sentence structure and are specifically trained for Twitter data.
- Measure error rate: Label a small validation dataset to test the model and measure the error rate of the sentiment analysis step.
- Consider user country: Explore the country field in the input data to study each country's sentiment separately.
- Refine Twitter hashtag topics with NER: Use Named Entity Extraction (NER) to extract topics and refine the understanding of what contributes to people's sentiment.
- Use advanced data mining tools: Leverage newer NLP techniques such as BERT for topic mining instead of the LDA algorithm.
- Improve processing speed: Optimize the code to handle a larger volume of tweets and improve processing efficiency.
- Expand study to other languages: Extend the analysis to include tweets in languages other than English.
- Deeper exploration of user profile information:


  1. Utilize the friends_count and followers_count to quantify the tweet's social media influence.
  2. Analyze the reply_to_screen_name field to determine connected components of people retweeting each other.

## What We Learned

Through this project, we gained the following insights and skills:

- General approach to sentiment analysis
- Utilization of NLTK, Vader, and TextBlob libraries for sentiment analysis
- Working with Pandas, Matplotlib, and other NLP packages
- Handling and processing a large dataset with efficient sampling techniques

## Contact

If you have any questions, suggestions, or would like to connect, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/neeleshvashist/). You can also fork this project on GitHub: [Covid-19 Sentiment Analysis](https://github.com/NeeleshVashist/Covid-19-Sentiment-Analysis).

Your feedback and contributions are highly appreciated!

---

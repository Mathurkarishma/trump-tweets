<!-- PROJECT LOGO -->
<p align="center">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Donald Trump Tweets</h3>

  <p align="center">
    What kind of emotions do his tweets convey?
    <br />
    <a href="https://github.com/Mathurkarishma/trump-tweets"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Mathurkarishma/trump-tweets/issues">Report Bug</a>
    ·
    <a href="https://github.com/Mathurkarishma/trump-tweets/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#conclusion">Conclusion</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The aim of this study is to analyze Trump’s content message strategies and evaluate his aggregated sentiments toward a given topic using sentiment analysis.  Sentiment analysis algorithms are used to categorize opinions in a given text by classifying words into categories. Because tweets are very noisy, the dataset at hand is a high sparseness and high dimensional dataset.  This could reduce the efficiency of the K-means algorithm.  This problem will be overcome by selecting relevant features using term frequency-inverse document frequency (tf–idf) technique, and reducing the high dimensional dataset using principal component analysis (PCA), while retaining the most relevant elements.

### Built With

* [R](https://cran.r-project.org/)
* [RStudio](https://rstudio.com/)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running, download the `sentiment_analysis.R` and the text input file, `donald_tweets.csv`. Then run the code in an IDE software, such as RStudio.  Set the working directory to the location of the CSV file.

<!-- USAGE EXAMPLES -->
## Usage

The code guides you through the following:

1. Importing the CSV file
2. Visualizing the formatting of the variables (datatypes, number of rows/columns, measures of central tendancy, statistical descriptions, etc.)
3. Create a corpus to store dictionary of texts
4. Text pre-processing such as installing packages, cleanup, transformation, and normalization (remove unique identifiers and irrelevant variables, cleanse errors such as special characters and stopwords, etc.)
5. Exploratory analysis such as sentiment analysis based on the NRC Word Emotion Association Lexicon from tidytext package or the bag of words model
6. Transformation into Document Term Matrix and Term Document Matrix, to allow for frequent terms to be found easily, and creation of a word cloud, box plot, and histogram
7. Perform the K-means clustering algorithm and evaluate through the elbow method and optimal K
8. Visualize through a cluster plot and cross tabulation for comparison
9. Evaluate sentiment score on all tweets
10. Generate top 5 words from each cluster, which suggests general topics the tweets are about

<!-- CONCLUSION -->
## Conclusion

The top sentiments expressed by him were positivity and trustworthiness, which allowed him to build a strong and loyal base.  He was able to capitalize through them by using words in his tweets to create calls to action.  He followed the same word usage and patterning as the clusters generated from the analysis overlapped and had similar words captured in them.

<img src="images/sentimemnt.JPG" alt="sentiment">

<!-- CONTACT -->
## Contact

Karishma Mathur - karishma324@gmail.com

Project Link: [https://github.com/Mathurkarishma/trump-tweets](https://github.com/Mathurkarishma/trump-tweets)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* Group Members:  Grant Lum, Vanessa Fotso, Brandon Clark </br>
* Dr. Firdu Bati at [University of Maryland, Global Campus](https://www.umgc.edu/) - Fall 2019 </br >

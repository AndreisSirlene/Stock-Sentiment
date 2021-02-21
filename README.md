# 📈 Stock-Sentiment
Stock Sentiment from news Headlines

> "The way to get started is to quit talking and begin doing." - Walt Disney


# :pushpin: Table of Contents

* [Introduction](#memo-introduction)
* [Exploratory Data Analysis ](#rocket-exploratory-data-analysis)
* [Exploratory Visualizations](#tada-exploratory-visualizations)
* [License](#closed_book-license)

# :memo: Introduction

In this notebook, we will generate investing insight by applying sentiment analysis on financial news headlines from [FINVIZ.com]. Using this natural language processing technique, we can understand the emotion behind the headlines and predict whether the market feels good or bad about a stock. It would then be possible to make educated guesses on how certain stocks will perform and trade accordingly.
As web scraping requires data science ethic, the HTML files for Facebook and Tesla at various points in time have been downloaded from FINVIZ.

# :rocket: Exploratory Data Analysis 

The interesting data inside each table row (<tr>) is in the text inside the <td> and <a> tags. 
So we parse the data for all tables in a comfortable data structure.
Sentiment analysis is very sensitive to context.
Remember that the reason we chose headlines is so we can try to extract sentiment from financial journalists, who like most professionals, have their own lingo. 
  
Make NLTK think like a financial journalist by adding some new words and sentiment values to our lexicon.

# :tada: Exploratory Visualizations

 To visualize the positive, negative and neutral scores for a single day of trading and a single stock either for Facebbok and Tesla I used Matplotlib.
 We will make an informative plot where we will see the smallest grain possible: headline and subscores.


# :closed_book: License

Released in February 2021.
This project is under the [MIT license](https://github.com/AndreisSirlene/Stock-Sentiment/blob/master/LICENSE).

Made with love by [Sirlene Andreis](https://github.com/AndreisSirlene) 💚🚀

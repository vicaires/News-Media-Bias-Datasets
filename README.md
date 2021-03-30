# News Media Bias Datasets

We share here four different datasets, classified by their approach: links between domains and text (content) of articles. Next, we describe these datasets by their structure.

## Link-based dataset

This dataset was created by extracting hyperlinks from news articles. Unfortunaly, we don't have the source HTML files, including the whole content. So, we share two files in the Link-based directory:

* `links_news_july_2019.csv`: this file includes all links from one source to another. This file can be read by multiple graph analysis softwares, such as Gephi and NetworkX (a popular Python library to manipulate graphs). The result will be a directed and weighted graph, where the nodes (vertices) are websites, and the links (edges) are hyperlinks from one website to another, as extracted from news articles.
* `urls_news_july_2019.csv`: here, we included the news articles URLs, allowing the possibility of downloading the articles for other manipulations, such as hyperlink and content extraction.

## Text-based datasets

These datasets are more structured and organized in a CSV format, facilitating handling the data in different contexts. All three datasets have the following structure:

* Source: the website that published the news article.
* Title: the title of the news article.
* Content: all the textual content of the news article.
* Bias: the ideology, as reflected by Media Bias Fact Check (https://mediabiasfactcheck.com/) by the time of their crawling.

Each dataset was crawled in a different timeframe and can be used to compare how opinion from multiple sources has evolved through time.

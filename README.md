# Case study : Mining NASA Metadata Overview

* Metadata is a term that refers to data that gives information about other data.

* In this case, the metadata informs users about what is in these numerous NASA datasets but does not include the content of the datasets themselves.
* Purpose: Use word cooccurrences and correlations, tf-idf, and topic modeling to explore the connections between the datasets.

  * Can we find datasets that are related to each other?
  * Can we find clusters of similar datasets? ..

# Data and Source

* The data from : https://data.nasa.gov/data.json

* Program : **R** studio (Rmarkdown)

# Process

* Wrangling and Tidy the data (seperate the meaningful data for description, title and keywords)

* Tokenization _ Remove stopwords

* Word Co-ocurrences and Correlations

* Calculating tf-idf to identify words that are especially important to a document within a collection of documents

* Topic Modeling : LDA

# Some Findings

**Co-ocurring words for Title**

![RStudio 9_26_2022 6_56_11 PM](https://user-images.githubusercontent.com/99704273/192248317-fbf990fc-c7a2-48e1-9826-fe3fc2557ef3.png)

**the network of keyword correlations**

![RStudio 9_26_2022 6_58_46 PM](https://user-images.githubusercontent.com/99704273/192248801-557e6ecd-563d-442c-9d53-3f93e9a6f43e.png)


![R Graphics_ Device 2 (ACTIVE) 9_26_2022 7_02_31 PM](https://user-images.githubusercontent.com/99704273/192249532-fcc2a512-8ee7-4756-8946-d5894545f187.png)

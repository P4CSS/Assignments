# Scraping twitter data dand doing exploratory data analysis

## Part 1
* Getting twitter data by rtweet library. Visit [http://rtweet.info/](http://rtweet.info/) to know functions you can use. Try to take use of functions to get meaningful data to specific questions.
  * You should select a topic and scrape at least 1000 tweets. Run and show dimension and structure of your data. Also, provide the most basic data summarization by `count()`.
  * e.g., Search then get important users or keywords then search again or crawl user timeline one by one.
  * (Advanced) Some of functions are designed for getting data by stream API. If you're really interested in programming, you're encourage to use `stream_tweets()` function based on twitter Stream API. I'm very interested in the coverage and capabiity of stream method.

## Part 2
* Doing exploratory data analysis by ggplot and dplyr pipeline syntax to show some descriptive evidences. Please provide at least three charts. 
* You can create new categorical variables by `mutate(new_var = ifelse(conditionA, "A", "B")) then treat it as a type to fill or plot them separatedly.

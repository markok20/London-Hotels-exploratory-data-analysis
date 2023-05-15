# London-Hotels-exploratory-data-analysis
London Hotels customer reviews exploratory data analysis

Feedback data tells: which hotel in London has the best customer experience?

Are you planning a trip to London in the summer? Do you want to know which hotel has the best customer experience based on the sample? Which hotels do customers rank first? Which factors do customers value most in a hotel: location or service? Which means more?

I sought answers to these questions when I went through the open data of London hotels, which included a dozen hotels from both the most expensive and the cheapest end. I retrieved the data from the data.world database, where the information had been collected from the pages of the tourism portal during the years 2012-2018.

The material can be found at:

https://data.world/promptcloud/customer-of-reviews-of-london-based-hotels

There were a total of 27,330 lines in the entire material. I limited the data by removing the feedback that did not contain English from the opinions. After the cuts, the number of lines dropped to 23,578. I processed the data with Python. At the end of the article there is a link to the Python code.

So which hotel has the best customer experience? In the data, hotel visitors evaluate the customer experience on a rating scale (1=bad – 5=very good. Based on the results, the customer experience is at a good level, because the majority rated the experience either 4 or 5.

Which words were repeated the most in the feedback? One method of visualization is a word cloud. The larger the font, the more often the word appears in the response data. From the word cloud, you can see that, among other things, service ability, location, staff, service attitude, restaurant, bar, good and lovely are at the top of the list. The weakness of the word cloud is that it is difficult to determine density values exactly.

Another way is to lemmatize, i.e. basic form the words and highlight the most frequent words.

Another way is to use the n-gram algorithm, which calculates the most common words from the data.

Conclusions:

Hotel guests value a friendly, service-oriented customer experience more than the hotel's excellent location.

However, location does matter. Visitors appreciate the location at the foot of the metro station.

Breakfast matters. Visitors like to enjoy an English breakfast.

Good landmarks near the hotel include Kensington, Hyde Par and Royal Albert Hall.

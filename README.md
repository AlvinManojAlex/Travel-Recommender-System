# Travel-Recommender-System

The project aimed to create a robust hotel recommendation system based on user preferences and city choice. The primary challenges included efficient web scraping from the dynamic Google Hotels page, data cleaning to handle variations in feature descriptions, and implementing a content-based recommendation model for personalized suggestions.

### Web scraping with Selenium:

● Selenium was used to automate the web browser and extract information from the
official Google Hotels page.

● Selenium navigated through the webpage, entered the user's chosen city, and collected
hotel data.

● Class names, ID selectors, and other HTML attributes were used to locate and extract
relevant information such as hotel names, prices, ratings, and features.

● The scraped data was then transformed into a structured format, such as a pandas
DataFrame, for further analysis and recommendation

### Content based filtering:

● Content-based filtering was employed to provide hotel recommendations based on the
similarity between a user's preferences and the features of different hotels.

● Features were transformed into binary values (0 or 1) to create feature vectors for
each hotel.

● Cosine similarity was calculated between the feature vector of a user's query and the
feature vectors of hotels in the dataset.

● The hotels were ranked based on cosine similarity, and recommendations were
provided from the most to least similar.

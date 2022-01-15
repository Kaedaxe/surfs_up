# Weather Analysis with SQLalchemy

## Analysis
The objective of this project is to determine the viability of a surf and ice cream shop in O'ahu, Hawaii. To do so, we must understand the expected temperatures of O'ahu during the peak of summer and winter. We utilize SQLAlchemy to import and query a SQL table in python, using a SQLite file of historical weather data stored locally. The temperature data of June and December in the years 2010 to Mid-2017 (excluding December) is imported as two lists respectively, which are converted to Pandas DataFrames and statistically analysed using the .describe() function. 

## Results
* Temperatures in June are on average very warm, as expected

![image](https://user-images.githubusercontent.com/77989740/149637198-604cbd48-b452-405e-8b2a-da18bf5688b0.png)

* Temperatures in December remain solidly high with the exception of some mildly cold days

![image](https://user-images.githubusercontent.com/77989740/149637256-2833eb4a-a0a5-41e2-bc53-4ecbb182c29e.png)

* There's a higher degree of variance in December. While the warmest days are approximately the same as June, the coldest can have significantly lower temperatures.

## Summary
A surf and ice cream shop could see success in a location that's warm even in winter. There may be slower days during winter, especially when middling temperatures are more impactful to a local populace accustomed to warmth. Two additional queries that might improve on this conclusion could be finding how many days per year O'ahu sees heavy precipitation and what months would see the most/least days of heavy precipitation.

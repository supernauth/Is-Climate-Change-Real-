# Is Climate Change Real?
It has become trendy in Hungary to claim the climate change is just nut present, that it's just a hoax.
I never thought so, but I wanted to make an analysis with the help of the available datasets to see what we can feel during many days.

## Datasets
<a href='https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data'>source #1: kaggle.com: Climate Change: Earth Surface Temperature Data</a>  
<a href='https://www.wunderground.com/history/monthly/hu/budapest/LHBP/date/2013-1'>source #2: Weather Underground</a>  
<a href='https://www.met.hu/en/eghajlat/magyarorszag_eghajlata/eghajlati_adatsorok/'>source #3: Hungarian Meteorological Service: Climate Data Series 1901-2020</a>  
The kaggle dataset is quite broad, but it was only until 2013, so I needed to use the Weather Underground's information for the temperatures.
I used the Hungarian Meteorological Service's dataset for the precipitation calculations.

## The temperature analysis
The kaggle dataset is about many cities around the globe, but I decreased the data only for Hungarian cities, then filtered out the NaN values.

First, I examined the yearly average temperature for each city. As I expected, I discovered that they are parallel. Besides, an increase beginning from the 1970's could be seen as well.
I made a separate plot about the time period from the 1970's. The parallelism can be clearly seen, we can see that the increase is even steeper from 2006-2011.
I made another plot to check if the parallelism is still present examined month by month. It is, so I went on only with Budapest's dataset. At this time, the absence of the data from 2014 bothered me, so I looked for another data source, I found Weather Underground's dataset.

Continuing with the expanded dataset, the rise which began in the 1970's is more spectacular. There are some high and low values, but looking at the 5-year average, the trend is unequivocal.

### Analysis of season's change
People like to say that seasons' position have moved, but it is hard to remember how exactly things happened long ago. One's memory can fail him/her.
In order to see this, I analysed the separate months' average, from 1755 and from 1970.

Looking at the two multiplots, I see that every month's temperature have risen, but the 3 summer months have the strongest increase.
Following from these, I would not say that the seasons moved, the spring we have now is the now spring, the summer is even hotter. The present spring is just much alike the summers we used to have before.

## The precipitation analysis
For this purpose, I used the Hungarian Meteorological Service's Climate Data Series (1901-2020), expanded the analysis for 5 cities.

People say that we have fewer rains with bigger amount of precipitation. For this, I calculated the average amount for the days where there were any precipitation. Looking at the plot, I could not say that I see a trend for this.
To give a second chess to the hypothesis, I also calculated the number of rainy days for each year, but it is even more permanent.
I made another plot for the yearly maximum precipitation, but I would not draw a conclusion.
The last plot is about the days where there were more than 20 mm precipitation, with a 5-year moving average. I see a slight decrease instead of an increase, but the average is rather flat.

# Conclusion
I must say that the temperature is clearly rising, unfortunately. It has some little variability, but the trend is clear.
Regarding the precipitation, I cannot say that there is any severe change what I can see in the datasets. The average amount and its distribution is also quite constant.

# Future plans
People like to say that we have stronger winds than before, so it would be useful to examine this, but I could not find any good dataset about that, yet.
The newest frequent phenomenon is the desert sand in the atmosphere abova Hungary, but I am unaware of any statistics regarding that topic.
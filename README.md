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
I made another plot to check if the parallelism is still present examined month by month. It is, so I went on only with Budapest's dataset. At this time, the absence of the data from 2014 bothered me, so I looked for another data source, I found the Hungarian Meteorological Service's dataset.

Continuing with the expanded dataset, the rise which began in the 1970's is more spectacular. There are some high and low values, but looking at the 5-year average, the trend is unequivocal.
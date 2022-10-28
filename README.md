# Traffic indicators on I-94  - WIP
Guided Project: Finding Heavy Traffic Indicators on I-94

<!-- ![I-94](images/1200px-I-94_svg.png) -->
<p align="center">
<img src="images/1200px-I-94_svg.png" width="200">
</p>

Describe the project and add links
- [I-94 Interstate highway](https://en.wikipedia.org/wiki/Interstate_94)
- [UCI Machine Learning](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume)

What the project is about?

Your goal with this project:

"The goal of our analysis is to determine a few indicators of heavy traffic on I-94. These indicators can be weather type, time of the day, time of the week, etc. For instance, we may find out that the traffic is usually heavier in the summer or when it snows."

### What was done?

- Cleaning
- Removing outliers
- Fixing data types
- Exploring price in function of brands and vehicle types

### Credits

This is a guided project from the [DataQuest](https://www.dataquest.io/blog/free-datasets-for-projects/), from the Path `Probability and Statistics with Python`.


## Folders
- data: dataset in `.csv`
- images: pictures in `.png`
- code: notebooks in Python saved as `.ipynb`

## Setup

The code was made and run in the DataQuest platform using:
- Jupyter Notebook
- [pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/stable/index.html)

## The Dataset
Write about the dataset

Descriptions of the variables:   (Source:[
Metro Interstate Traffic Volume Data Set](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume))

- `holiday`: Categorical US National holidays plus regional holiday, Minnesota State Fair
- `temp`: Numeric Average temp in kelvin
- `rain_1h`: Numeric Amount in mm of rain that occurred in the hour
- `snow_1h`: Numeric Amount in mm of snow that occurred in the hour
- `clouds_all`: Numeric Percentage of cloud cover
- `weather_main`: Categorical Short textual description of the current weather
-`weather_description`: Categorical Longer textual description of the current weather
- `date_time DateTime`: Hour of the data collected in local CST time
- `traffic_volume`: Numeric Hourly I-94 ATR 301 reported westbound traffic volume

## References
- [Anatomy_of_a_graph](https://matplotlib.org/stable/tutorials/introductory/quick_start.html)
- [Scatterplots-Mathisfun](https://www.mathsisfun.com/data/scatter-xy-plots.html)
- [Scatterplort-catalogue](https://datavizcatalogue.com/methods/scatterplot.html)
- [Correlation-Mathisfun](https://www.mathsisfun.com/data/correlation.html)

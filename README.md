
<p align = center >  
  <img src = 'https://user-images.githubusercontent.com/75224625/113495748-cb97e980-94c9-11eb-986b-819c86d4a3a0.png' width = 300 height=300>
</p>

<h1 align = center>
  House Price Prediction on Airbnb
</h1>

<p align= 'center'> 
  <b>
    <a href ='#intro' > Intro </a>|
    <a href ='#contents' > Contents </a>|
    <a href ='#project' > Project </a>|
    <a href ='#contribute'>Contributing </a>|
    <a href ='#credits' > Credits </a>
  </b>
</p>

<h2>
  <a name="intro">Intro </a> 
</h2>

<h4 >
Airbnb is a community online service for people to advertise, discover and book accommodation and lodges.

Airbnb allows individuals to rent all or part of their own home as a form of extra accommodation. The website provides a search and booking platform between the person offering the accommodation and the tourist looking for the location. It covers more than 500,000 advertisements in more than 35,000 cities and 192 countries. Since its creation in November 2008 until June 2012, more than 10 million reservations have been booked via Airbnb.

 If you decide to rent your house, apartment or just share a room, you need to base yourself on the rent amount upon the average price for the site. But how is it possible to get nearly close to the price it should be just based on the Airbnb data? Predictions!

 Using a dataset from Airbnb it's possible to collect important informations, so, in this prediction I've choosen a way to extract these informations based in a plain person that want to rent a place with average low price.
<h3>

<h2>
  <a name="contents">Contents </a> 
</h2>

### For dependencies were imported:
* Pandas
* Numpy
* Seaborn
* matplotlib
* plotly
* sklearn

### Models:
* RandonForestRegressor
* ExtraTreeRegressor
* LinearRegressor

### Datasets

* [Airbnb Rio de Janeiro dataset](https://drive.google.com/drive/folders/1AapFnCef1eKfVglR3v6IGfjDmtWWtGno)


<h2>
  <a name="project">Project </a> 
</h2>

The objective of this project is basically understand what are the main features that has a relevant importance to obtain a rent price for normal houses
from plain people. 
Users from Airbnb can rent their houses or apartments while they are travelling, working abroad or simply has an empty room to share.
Airbnb can't predict the value you're going to rent the site, so, based in Rio de Janeiro Airbnb dataset, what are the average values to rent a place being a plain person? Being aware that a house, apartment, flat or even a small room can't compare with luxury homes and apartments. So to avoid these kinds of outliers is better analyse the dataset carefully.


### Joining all dataset's month in a single df 
<img src = 'https://user-images.githubusercontent.com/75224625/113953144-889d8500-97ed-11eb-9d84-8df52a6e0c86.png' width = 700 height=400>

___
### Creating functions to help detect outliears, limits and display graphically each feature.
* **sns.barplot**: Bar graphic 
* **sns.boxplot**: Box diagram
* **sns.distplot**: Histogram

<img src = 'https://user-images.githubusercontent.com/75224625/113953155-8c310c00-97ed-11eb-8497-154cedaced3a.png' width = 700 height=400>
___
### Amenities is one of the main features from this dataset, with 14 items that should be analysed with atention.

<img src = 'https://user-images.githubusercontent.com/75224625/113953167-918e5680-97ed-11eb-9876-1a94b4d997e1.png' width = 700 height = 400>

___
### Map view of properties in a data sample of 50000 random properties with plotly express and density_mapbox.
#### The current value/price is BRL R$.
<img src = 'https://user-images.githubusercontent.com/75224625/113953177-95ba7400-97ed-11eb-84f9-83ed7bf70c7d.png' width = 700 height = 400>

___
### Looking for the importance of each feature, it's possible to check that bedrooms and the place are the main causes for variation of renting value
<img src = 'https://user-images.githubusercontent.com/75224625/113953182-98b56480-97ed-11eb-8f38-c8029e5fcf6e.png' width = 700 height = 400>

In conclusion, the model got an expressive prediction over the 95%, this value can get higher because there are many features that implicates in the final value for renting a place.

<h2>
  <a name="contribute">Contributing </a> 
</h2>

1. **Fork the repository on GitHub**
2. **Clone the project to your own machine**
3. **Commit changes to your own branch**
4. **Push your work back up to your fork**
5. **Submit a Pull request so that I can review your changes**

<h2>
  <a name="credits">Credits </a> 
</h2>

[Hashtag Programação](https://www.youtube.com/channel/UCafFexaRoRylOKdzGBU6Pgg)

Copyright (C) 2020-2021 by **Cristian Santiago** 
___
![Visits Badge](https://badges.pufler.dev/visits/engcristian/Airbnb-Rio-Project)

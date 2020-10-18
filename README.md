<img style="float: left;" src="https://upload.wikimedia.org/wikipedia/en/thumb/8/84/University_of_Helsinki.svg/1200px-University_of_Helsinki.svg.png" width="100">

# HSL citybike predictor - Introduction to Data Science Project
<p align="center">Giacomo Greggio, Linda Hyvärinen, Antti Koivurova <br/>
  October 2020
</p>

## Real world issue:
How many times have you happened to reach a station to take a citybike and didn't find any of them available? <br/>
How much time did you loose to reaching a station and find a solution when you have realized that there are no citybikes available? <br/>
Besides, if the weather was not the best, probably it hasn't been a pleasant experience. <br/>
What would happened if you have a way to check the availability of the citybikes between the different stations based on some variables as instance the weather?

## Our solution:
Well, our final product is an application (or an add-on to a pre-existing HSL-application) that will give you the possibility to monitoring the availability of the citybikes in the different situations, by predicting for each hour the number of citybikes available in the closest stations and also based on other factors as weather, weekday and month.

## Preview of HSL citybike predictor application
Below there is a preview about the mockup of the mobile application "HSL citybike predictor". <br/>
<img src="https://github.com/giacomogreggio/HSL-citybikes-predictor/blob/master/images/app.jpg" width="200" height="400" />

## Partners
<img style="float: left;" src="https://www.hsl.fi/sites/all/themes/custom/hsl_tyyliopas/logo.png" width="130" />

Helsinki Region Transport (HSL) is a joint local authority whose member municipalities are Helsinki, Espoo, Vantaa, Kauniainen, Kerava, Kirkkonummi, Sipoo, Siuntio and Tuusula. HSL began its operations in 2010. <br/>
Some 370 million journeys are made on HSL's transport services annually. HSL's annual operating income is over €640 million, of which ticket revenue accounts for about €330 million (about 46% in 2016). HSL has 373 employees. <br/>
HSL provides open data on all the trips made with the citybikes. To out aim we used all the data related to the whole season of 2019.

<img style="float: left;" src="https://marine.copernicus.eu/wp-content/uploads/2019/02/il-logo-fmi-rgb-687x345px.png" width="100" />

The Finnish Meteorological Institute produces observation and research data on the atmosphere, the near space and the seas, as well as weather, sea, air quality and climate services for the needs of public safety, business life and citizens. The Finnish Meteorological Institute is an administrative branch of the Ministry of Transport and Communications. <br/>
Finnish Meteorological Institute provides open data on the weather that we used to do our predictions.

## Our data
For our predictions we use:
- the time of the day,
- current month,
- the area of the station,
- the day of the week and
- the weather.

All our data are provided by HSL and Finnish Meteorological Institute. <br/>
We ranked the weather in 10 different categories based on cloud cover, fog, amount of rainfall and windiness.

### Data behaviour and visualizations
From the first graph you can see the departures of every Monday in October 2019 from all the stations. It represents the general behaviour of our data. <br/>
<img src="https://github.com/giacomogreggio/HSL-citybikes-predictor/blob/master/images/october_behaviour.png" width="600" height="400" />

Next, we show you the number of departures and arrivals in the whole year 2019 divided per hours in one of the most famous citybike station in Helsinki: Töölönlahdenkatu. <br/>
<img src="https://github.com/giacomogreggio/HSL-citybikes-predictor/blob/master/images/popular_station.png" width="600" height="400" />

Also, we show you the same graph but for the citybike station that is one of the least crowded station: Itäkeskus Metrovarikko. <br/>
<img src="https://github.com/giacomogreggio/HSL-citybikes-predictor/blob/master/images/non_popular_station.png" width="600" height="400" />
 
One of the most important aspect of HSL citybike predictor is the weather. We provide below th graph with the relation between the departures/arrivals and the weather in 2019. <br/>
<img src="https://github.com/giacomogreggio/HSL-citybikes-predictor/blob/master/images/weather.png" width="600" height="400" />
 
The previous graph is proposed also with the relation between the other main variables as hours, months and weekday. <br/>
<img src="https://github.com/giacomogreggio/HSL-citybikes-predictor/blob/master/images/hour.png" width="600" height="400" />
<img src="https://github.com/giacomogreggio/HSL-citybikes-predictor/blob/master/images/month.png" width="600" height="400" />
<img src="https://github.com/giacomogreggio/HSL-citybikes-predictor/blob/master/images/weekday.png" width="600" height="400" />

## Problems/Solutions
Problems:
- It is difficult to choose which station to go to when you are looking for a bike.
- A lot of time is lost if you make the wrong choice.
- Transportation in Helsinki requires multiple mobile applications which is frustrating for the users.
- Route planners suggest routes without any regard for the availability of citybikes.

Solutions:
- Our aim is to give a solution for all the users of our application that reduce the time consuming and provide the best choice for the station.
- Our application is aimed to be an add-on to a pre-existing application.
- Our project makes it possible to suggest accurate routes taking the citybike availability into account.

## Same scope, different applications

## Credits
[Giacomo Greggio](https://github.com/giacomogreggio) <br/>
[Linda Hyvärinen](https://github.com/lindahyva) <br/>
[Antti Koivurova](https://github.com/akoivu)

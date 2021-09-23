# API's USED

## location-IQ

`*this is the description and the usage for* **locationIQ**`
* **locationIQ:** flexible enterprise-grade location-based solutions. they work with developers, startups, and enterprises worldwide serving billions of requests every day. This website provides an overview of the technical aspects of our API
they are sending many data types depends on the user requests so the user will get the data about the location and latitude and longitude and many things.
also, they are sending images for the country or the city
or anything the user asks for.


**`All the user requests that sent  to LocationIQ's APIs or Map tiles needs to be authenticated with an access token(authentiction key).`**

## **what is the authentiction key or access token.** 
**`note`*** :This authentiction declaration for all API's
<br>
authentication is the property obtained when performing a key establishment protocol ( Key Agreement and Key Management) and one entity has the assurance that only a particularly identified other party may possibly know the request or anything else about the key itself.
<br>
<br>
<br>
<br>

all the requests can be sent to any of the following **`endpoints`** or servers.

**locationIq has two servers.** 

* **Region 1: US**
GET `https://us1.locationiq.com/v1/search.php?key=YOUR_ACCESS_TOKEN&q=SEARCH_STRING&format=json`

* **Region 2: Europe**
GET `https://eu1.locationiq.com/v1/search.php?key=YOUR_ACCESS_TOKEN&q=SEARCH_STRING&format=json`




## weather-bit

*this is the description for **`weather-bit`**
<br>
With their Weather API, you can retrieve current weather observations from over 47,000 live weather stations, and historical weather data for the past 10+ years sourced from over 120,000 stations, doppler radar, satellite, and atmospheric reanalysis products. As well as highly localized weather forecasts for any point on the globe using the world's most trusted weather models!

the user can look up weather data by many methods including:
* **Latitude/longitude**
* **City name**
* **City ID**
* **Weather station ID**
* **Airport ICAO code**
* **Postal (zip) code for any country in the world**





the user could use this API for many reasons such as: 


* Cloud Coverage
* Weather Conditions
* Precipitation Rate
* Temperature
* Snowfall
* Visibility




all the requests can be sent to **`endpoints`**

GET = `https://api.weatherbit.io/v2.0/forecast/daily?city=CITY&key=KEY`



## TMDB (MOVIE)

*this is the description for**`TMDB (MOVIE)`***
The Movie Database (TMDB) is a community built movie and TV database. Every piece of data has been added by our amazing community dating back to 2008. TMDb's strong international focus and breadth of data is largely unmatched and something we're incredibly proud of. Put simply, we live and breathe community and that's precisely what makes us different.




They will let the user Discover movies by different types of data like average rating, number of votes, genres, and certifications. You can get a valid list of certifications.
 the user can Discover also supports a nice list of sort options they have started publishing some daily ID file exports. These are not, nor intended to be full data exports. Instead, they contain a list of the valid IDs you can find on TMDB and some higher-level attributes that are helpful for filtering items like the adult, video, and popularity values
in short, they will provide the user with all the data that he needs for the movies and TV shows `depends on his request`  






all the requests can be sent to **`endpoints`**

GET = `https://api.themoviedb.org/3/search/movie?api_key=<<api_key>>&language=en-US&page=1&include_adult=false`



<br>
<br>


##### resorcses used:
[weatherbit](https://www.weatherbit.io/)

[locationIQ](https://locationiq.com/)

[TMDB](https://www.themoviedb.org/)
# Violence datasets for the United States


This project makes available two violence datasets built with daily event data sourced from [Project GDELT Events Database](http://data.gdeltproject.org/events/index.html) and GIS data sourced from [OpenStreetMap](https://www.openstreetmap.org). These violence datasets cover all types of violent crime including reported sexual assault and are suited for social science research on crime and other related topics.

The GDELT event data was collected by a series of algorithms with day-level granularity. Please see the table below for algorithm version details.

| algorithm version | start date| end date| news article source URLs| geocoordinates|
| --- | --- |--- | ---| ---|
| v1 | January 1, 1979 | December 31, 2005| No | Yes
| v2 | January 1, 2006 | March 31, 2013| No | Yes
| v3 | April 1, 2013 | March 1, 2024| Yes | Yes

The OpenStreetMap GIS data was collected using [Nominatim API](https://nominatim.org/release-docs/latest/) and includes full geometry with all points, lines and polygons.

#### Datasets for USA

1. **violent events dataset - 1,523,964 records** of violent events in the United States between January 1, 2019 and March 1, 20124 recorded at the day-level and stored in json format. The total size of this uncompressed dataset is 2.20 GB.

|algorithm version| violent events | reported sexual assault
| --- |--- | --- |
|v1| 48,832| 2,807|
|v2| 390,697| 44,707|
|v3| 1,084,435| 120,083|
|total|1,523,964| 168,437|



2. **reported sexual assault GIS dataset - 163,169 records** of reported sexual assaults in the United States between January 1, 2019 and March 1, 20124 recorded at the day-level, integrated with GIS data, and stored in geojson format. The total size of this uncompressed dataset is 1.23 GB.

#### Time series of violent events per GDELT algorithm version
_GDELT algorithm v1: January 1979 to December 2005_

![violent events dataset v1](https://github.com/haayanau/USA_violence_datasets/blob/master/images/v1.PNG "Time Series Plot v1")

_GDELT algorithm v2: January 2006 to March 2013_

![violent events dataset v2](https://github.com/haayanau/USA_violence_datasets/blob/master/images/v2.PNG "Time Series Plot v2")

_GDELT algorithm v3: April 2013 to February 2024_

![violent events dataset v3](https://github.com/haayanau/USA_violence_datasets/blob/master/images/v2.PNG "Time Series Plot v3")


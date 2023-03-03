# Airbnb Prices in Europe Analysis

## Data
Link to the dataset: https://www.sciencedirect.com/science/article/pii/S0261517721000388?via%3Dihub#sec3

| Variables          | Description                                                    |
|--------------------|----------------------------------------------------------------|
| bedrooms           | 	number of bedrooms                                            |
| realSum            | 	price of the rental houses                                    |
| person_capacity    | 	maximum number of guests                                      |
| room_type          | 	type of room                                                  |
| room_private       | 	dummy for private rooms                                       |
| room_shared        | 	dummy for shared rooms                                        |
| cleanliness        | 	guest reviews: scale to 10                                    |
| guest_satisfaction | 	guest reviews: scale to 100                                   |
| superhost          | 	dummy for hosts with the superhost status                     |
| multi              | 	dummy for listings offered by hosts with 2–4 listings         |
| biz                | 	dummy for listings offered by hosts with more than 4 listings |
| dist               | 	distance to the city centre in kilometres                     |
| metro_dist         | 	distance to the closest metro station in kilometres           |
| attr_index         | 	attraction index: scale to 100                                |
| rest_index         | 	restaurant index: scale to 100                                |


## Libraries used
The following libraries are used in this analysis:

* pandas
* numpy
* matplotlib
* seaborn
* sklearn
* time
* statsmodels
* glob
* thnkstats2
* thnkplot
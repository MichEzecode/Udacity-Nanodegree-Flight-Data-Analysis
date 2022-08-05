## Flights Data Exploration

### Dataset

>The data consists of information regarding flights data in the USA for year 2008 from January - April.

>The dataset contains a total of 2389213 entries with 25 variables which all seemed interesting to analyze but for the purpose of my analysis i will be focusing on the delay variables such as ArrDealy, DepDaly,Carrier Delay and othres, Airtime, Distance , Cancellation and enginr_type variables.

### Data Wrangling

>From my research, I found out that flights delayed after 15 minutes is considered a delay therefore I queried all arrival delays after 15mins and used it as the basis of most of my analysis.
In other to get the engine types of the airlines used I merged the 2008 dataset with the plane dataset using the Tail Number variable present in the two datasets. To achieve this I renamed the Tail Number column to match both datasets.

>To also reduce the bulkiness of my dataset I had to drop some columns not needed for my analysis.




### Summary of Findings

### Univariate Exploration

>This part of my analysis was used to get familiar with my variables of interest.

>Firstly, I used a bar chart to show the total number of flights for each airline for the period covered in my dataset after which with the aid of a histogram I was able to see the distribution of some variables such as airtime, distance and delays both with the normal scale and log scale. It was observed that the delays (Arrival, departure and other delay types were all right skewed with long tails except security delay which had a shorter tail.

>Further exploration of my dataset showed that the proportion of cancelled flights was little compared to the total number of flights this was visualized with a pie chart while the major cause of this cancellations was determined and visualized with a bar chart with weather(A) being the top player and security the least.

>The engine types used by this airline were also determine and the type used frequently by most airlines.The last analysis for this part of my exploration shows the average number of delays for each of the delay types and it was deduced the weather delay had the highest delay timeline.




### Bivariate Exploration

>With tha aid of a bar plot I was able to show the average delay in minutes for each carrier based on the delay types. It was an interesting one as it seemed airlines with fewer number of carrier delays had smaller amount of aircrafts when compared to others. Also those with higher minutes for weather delay seemed to have more of the Turbo prop engines. The number of aircrafts per airline was visualize using a heat map.

> A barplot was then used to visualize weather and carrier delay aganist engine types and Turbo prop enginr types topped the chart of engine that causes the most delays.

> A violin plot was then used to visualize which delay type causes the most arrival delay and weather again topped the list.

> Since weather topped the chart as the chief delay officer,  I used a point plot to establish which month and day of the week tends to be more prone to weather conditions that could possible after the arrival time of aircrafts and found out the highest points were in February and Friday respectively.

### Multivariate Exploration

>Three visualizations were used in this stage of my exploration. The first showed the Arrival delay experienced by each airline for the different delay type and as we have its weather delay lead that list again while security was shown to be the least for most airline.
The second which was visualized using a scatter plot was used to show if the distance between airports influenced arrival delays but there wasn't any relationship. Therefore, it's okay to say the longer of shorter the distance between the airports, has no influence on arrival delay.
Finally, a box plot was used to determine the effect of engine types on the different types of delays. It seemed Turbo Prop engine had the highest rate of delays amongst other engine types.



### Key Insights for Presentation

>For my presentation I’ll focus on the delays and the factors that may influence delays. I'll start by introducing the total number of unique carriers, followed by the different types of delay experienced.

>I'll also introduce total amount of flights cancelled and the major reasons for cancellation.

>Afterwards I’ll introduce possible factors that can influence or cause delays with focus on engine type variable. Here I’ll show types of engines used by the airlines.

>My presentation will convey all important information with the right plots to make all points made clear.




```python

```

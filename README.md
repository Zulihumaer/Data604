# Data604
Traffic Accidents in Chicago
The purpose of this research is to investigate traffic trends and outline factors impacting the volume and intensity of traffic accidents in two major cities: Toronto and Chicago.

My part of the analysis is "Chicago crush data" 

Link for dataset: Traffic Crashes - Crashes:https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

Parameters before wrangling: Size ~350MB, 49cols x 674K rows, 9 years (2013-2022)

Parameters after wrangling: Size ~96MB, 26cols x 317Krows,3 years (2019, 2021, 2022)

Data Cleaning and preparation: since this dataset is pretty big, it is difficult to load into MYSQL. 
Therefore,I used pandas to clean it up by parsing the CRASH_DATE to YEAR, MONTH and DAY,selecting the year 2019,2021,2022 and crash related factors by dropping information that is not signifiantly correlated with car crash.

There are several reasons why I choose this dataset. 

Firstly, we all want to explore the car accident related factors and we choosed two big cities in Canada and US to see the similarities and differences between them. 

Secondly, I have never been to Chicago before and I read from news that the number of traffic deaths in Chicago rose from 113 in 2016 to 133 in 2017, an increase of 18 percent. The car crashes is a big cconcern there. So, I am really intersted in understanding the situation there and this exploration might be a good suggestion for people and friends who live in Chicago.Discovering patterns in accidents may help determine if procedures need to be altered to keep people and property safe. Sharing information and discoveries helps to prevent future accidents and can reduce risks for others. 

Thirdly, this dataset is not too huge for my computer to handle it. 

Summary: from this project, I have leanred a lot about SQL and this language helped me explored this interesting topic.
After data exploration, I had many findings and these findings also matched with the research for the pandemic on car accidents. For example, the COVID-19 pandemic has generally reduced the overall absolute numbers of road traffic collisions(RTCs), and their deaths and injuries despite the relative increase of severity of injury and death.The primary causes for car accidents in Chicago is failing to yeild right of the way and under wet and darkness condition, they might together contribute to higher accident numbers.

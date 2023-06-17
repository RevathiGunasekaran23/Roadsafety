## ROAD SAFETY ANALYSIS AND VISUALIZATION USING TABLEAU				
						
### Brief Introduction:

The goal of project is to address the pressing problem of road safety by identifying the key factors that contribute to the severity of road accidents. By determining these critical factors, we hope to reduce the number of accidents and fatalities over time. 

The entire project answers two questions:
1. Identifying the most important factors for predicting the severity of road-accidents
(Predictive analysis)
2. Exploring the data to group into homogeneous clusters based on the significant
variables (Exploratory analysis)

### Analytical Methods Used In Data Mining Process:

Data Source: https://www.kaggle.com/datasets/qasimhassan/reducing-the-number-ofhigh-fatality-accidents?select=accident-data.csv

**Data cleaning, preparation, and modification:**
1. Performed the correlation analysis on the numeric columns and found no issues and no close correlation between any two variables.  
2. Transformed the excel data to SAS format and started performing data exploration using various nodes like statexplore, optimal, best, maximum normal, default, tree, principal components, variable clustering and variable
selection.


**Data Visualization:**

The first visualization is based on looking at the number of accidents classified by the
accident severity in the region - urban or rural on a quarterly basis.  Comparatively,
less number of accidents happened in the quarter 2 of 2020 in terms of months. With respect to
accident severity, most accidents were of slight level of severity on the scale of slight, serious
and fatal. On the other hand, the majority number of accidents took place in the urban regions
compared to the rural regions. We then used packed bubbles to have a better visualization that
can easily depict the ratios.
<p>&nbsp  </p>
<img width="1200" alt="Screenshot 2023-06-17 at 1 14 24 PM" src="https://github.com/RevathiGunasekaran23/Roadsafety/assets/121855500/31faddbe-f5bf-4920-86d4-f53c8a91ce3b">


<p>&nbsp  </p>



<img width="1200" alt="Screenshot 2023-06-17 at 1 01 03 PM" src="https://github.com/RevathiGunasekaran23/Roadsafety/assets/121855500/ac54fddd-c25c-48c6-9d84-e43966abdb5f">

<p>&nbsp  </p>

The second visualization is focused on knowing how the number of accidents has ranged
in terms of severity on a daily basis of a week in different quarters. We found that the number of
accidents, irrespective of the quarter, have seen an increase in general from the beginning of the
week and plummeted by the end of the week. On the whole, as we mentioned above, quarter 2
has the lowest number of accidents on a quarterly basis. We used line graphs to visualize this
case.

<p>&nbsp  </p>
<img width="1200" alt="Screenshot 2023-06-17 at 1 01 45 PM" src="https://github.com/RevathiGunasekaran23/Roadsafety/assets/121855500/98401b0b-f5c3-40de-b20f-44db47bcf399">

<p>&nbsp  </p>
The third visualization is based on scaling the number of accidents based on two different
variables. We wanted to see how road surface conditions and road type have contributed to the
number of accidents. We used a tree map to visualize this case and found that major causes of
accidents in terms of road type were - single carriageway, dual carriageway and roundabout and
in terms of road surface conditions were - dry, wet/damp and frost/ice road surfaces.
<p>&nbsp  </p>
<img width="1200" alt="Screenshot 2023-06-17 at 1 02 23 PM" src="https://github.com/RevathiGunasekaran23/Roadsafety/assets/121855500/708f3bce-ec09-4973-b42f-f9596f54fee0">





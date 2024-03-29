# Final-Project-Tableau

The FAA Wildlife Strikes (2015) dataset provides information on collisions between animal species and aircraft between January 2000 and April 2015. The data was analyzed using Tableau Desktop to draw insights into the issue.

## Project/Goals

Option 2 was selected using the FAA Wildlife Strikes, 2015 dataset. 

The goal of this project was to understand the data through visualizations and find relationships/trends that could shed light on the issue of wildlife strikes.

Guiding question: Where can efforts be focused to mitigate wildlife strikes?

## Process

1. Load excel data file into Tableau
1. Review data columns and datatypes
1. Create visualizations to understand relationships and trends in relationship to the guiding question
1. Order visualizations into a Tableau story with informative notes.

## Results

### Key Takeaways: Where can efforts be focused to mitigate wildlife strikes?

* Focus on birds as a main priority.
* Focus on key species that are strike and cost outliers for prevention/mitigation efforts:
  * Birds  - Canada Goose, Mourning dove, Gulls, Barn Swallow
  * Bats - Vesper bats, Microbats, Brazilian free-tailed bat
  * Terrestrial mammals - White-tailed deer, Coyote
* Focus efforts in New York, Colorado, California, Florida, and Oregon.
* Increase awareness in Spring/Summer months. FAA runs an awareness campaign to have people report strikes.
* Increase awareness/checks during daytime flights.
* Look into mitigation for take-off, approach, and landing roll phases of flight.

### Sub-questions asked to approach main question 
#### Is there anything unique about where strikes are occurring?

**Visualizations used:**
* Map showing dollar cost of strikes for each U.S. state with colour scale. Size of the circle on the state shows the number of airports in the state.

**Findings:** 
* New York state has the highest dollar cost from wildlife strikes even though surrounding states have a comparable number of airports.
* Other states with high cost are Colorado, California, Florida, and Oregon.

#### Which species are affected by the strikes?

**Visualizations used:**
* Scatterplot of dollar cost vs. number of strikes for species.

**Findings:** 
 * Of the 4 animal categories (bats, birds, reptiles, terrestrial mammals), birds account for the most strikes. 
 * Some birds have a high number of strikes (e.g. Mourning Dove, Gulls, Barn Swallow) but relatively low dollar cost. However, the Canada Goose has only 564 strikes out of 28,298 but accounts for almost $80M in dollar cost.
 * Bats have fewer strikes but a similar pattern. Vesper bats have a lower number of strikes than other bats but result in a greater dollar cost.
 * For terrestrial mammals, white-tailed deer have a high number of strikes and dollar cost. Coyotes have a high number of strikes but compartively less dollar cost.
 * Reptile strikes are much lower and result in no recorded dollar cost.

#### What are the effects of wildlife strikes on aircraft?

**Visualizations used:**
* Piechart of indicated damage (caused damage or no damage). 
* Horizontal bar chart of the impact to flight based on number of strikes and the dollar cost of the strikes.
* Horizontal bar chart of the detailed amount of damage category based on number of strikes and dollar cost of the strikes.

**Findings:**
 * Across all animal categories only 10.99% of all strikes cause damage. However, for terrestrial mammals 27.84% of strikes cause damage.
 * When damage occurs it is most often classified as minor, and just over 50% of the time does not impact the flight. However, about 35.31% of the time, a flight may be aborted, have an engine shut down, or result in a precautionary landing.
 * When the damage is classified as substantial, 56.82% of flights are aborted, have engine shut down, or result in a precautionary landing. Substantial damage results in $224,781,943 worth of cost.

#### When are strikes occurring?

**Visualizations used:**
* Line chart for year over year trend, with forecast for next 2 years.
* Bar chart to plot number of strikes against time of day and phase of flight.

**Findings:**
* Over the years the number of strikes have increased.
* Strike frequency begins to increase from the start of the year and typically peaks in the summer, before decreasing again. Forecasting predicts the increase will and peak pattern will continue.
* On a smaller scale, most strikes occur during the day, and during the takeoff, approach, and landing roll phases of flight.

## Challenges 
* Null values for some fields (although most of the data had values)
* Unclear what some of the categories meant and no term glossary

## Future Goals
* Add animations, images, and URLs.
* Experiment with other colours and tooltips. 
* Update dataset as newer data is available.

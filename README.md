# Masters2022_ModelingWinnersOdds

The output of the 'SUM' Column gives the percent chance the player has of winning.  Talor Gooch has the best chance of winning based off the data used with an 8.95% chance.  His odds as of April 5, 2022 are +13000.
The data I scraped off of the PGA Tour website was the current Year-to-Date Stats of the metrics that are the most influential of determining success at Augusta (based on the following image): 

![Skillset Required for Augusta](https://www.sportsgamblingpodcast.com/wp-content/uploads/2022/04/relative-skill-set-chart.jpg)
Source: sportsgamblingpodcast

The idea of the model was to weigh each metric used from the image based on the percent given on the chart, calculate all of the metrics on a relative scale (-1,1), and then sum up the all of these metrics.  Finally dividing an indivual player's total 'SUM' score by the sum of all 'SUM' scores gives us the percent chance that the player will win based solely off of these factors.

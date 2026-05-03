# Fantasy Football Draft Value Analysis

## Overview
This project analyzes fantasy football player rankings by comparing official rankings to expert consensus. The goal is to identify where meaningful differences exist and highlight players who may be overvalued or undervalued going into a draft.


## Data
The dataset consists of 2026 fantasy football rankings sourced from FantasyPros. The key variables used in this analysis include:
- Official player ranking  
- Average expert ranking  
- Player position  

The analysis focuses on the top 100 players to keep the results relevant to actual draft decisions.


## Methodology

### Data Preparation
The data was cleaned and prepared using pandas. This included renaming columns, converting rankings to numeric values, and removing incomplete rows to ensure accuracy.

### Value Metric
To compare rankings, a value metric was created:

value = average expert rank − official rank

This measures how much a player’s ranking differs from the expert consensus.

- Positive values suggest the player may be ranked too high (overvalued)  
- Negative values suggest the player may be ranked too low (undervalued)  

### Analysis
The analysis focuses on:
- How closely rankings align overall  
- Which players stand out as clear outliers  
- Differences in ranking consistency across positions  


## Results
Most players show relatively small differences between rankings, indicating general agreement across sources. However, a smaller group of players stands out with larger discrepancies.

These outliers are the most important part of the analysis:
- Undervalued players may present strong draft opportunities  
- Overvalued players may carry additional risk  

There are also noticeable differences across positions, with some showing more variability than others, suggesting greater uncertainty in those evaluations.


## Visualizations
The project includes several visualizations to support the analysis:
- Histogram showing the distribution of value scores  
- Boxplot comparing value across positions  
- Scatter plot of official rank vs expert rank  
- Bar chart highlighting the most undervalued players  


## Conclusion
While fantasy football rankings are generally consistent, the differences that do exist can be meaningful. By focusing on these discrepancies, it’s possible to identify potential draft advantages and make more informed decisions.

## Tools
- Python  
- pandas  
- matplotlib  


## Author
Blake Tracy  
The Ohio State University — Economics Major, Statistics Minor

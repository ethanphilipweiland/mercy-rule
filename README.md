# Mercy Rule? Predicting the Full Time Result from the Half Time Result in the English Premier League
A team in the English Premier League has signed some young players. In order to optimize their playing time, the coach wants to be able to predict full time result at half time, so if the game is already won (or lost) the young players can see the field. To determine how predictable full time result is at half time, this research analyzes data from every match of the 2018/2019 Premier League season. Cross-tabulations, data visualization, and statistical inference reveal that full time result is indeed related to half time result, the home team wins more often than not, and the point of the season does not influence the probability of a certain full time result. A machine learning model - a decision tree for classification - is trained to incorporate these findings with other match statistics to best predict full time result. The model visualizes as a flowchart that the coach can easily trace based on match characteristics and predicts home wins well, away wins moderately well, and draws poorly. Overall, the findings of this analysis combined with the coach's subject matter expertise will optimize the amount of development time for the new young players.

## Analytical Report
The file notebook.ipynb contains a written description of the motivation, methodology, analysis, and results of this project.

## Necessary Software
You will need the following software and packages installed to run the code and reproduce the analysis.

Necessary software: `R`, `Jupyter Notebook` 

Necessary `R` packages: `tidyverse`, `ggthemes`, `tree`

## File Description
    1. /data/soccer18-19.csv : Data on each match from the 2018-2019 Premier League season. Downloaded from DataCamp Workspace (https://www.datacamp.com/workspace)
    2. notebook.ipynb : Written description of the motivation, methodology, analysis, and results of this project. Also includes all `R` code.

## Acknowledgements
An Introduction to Statistical Learning with Applications in R, by G. James et al. 2nd Ed. 2021

The idea and data for this project came from [DataCamp Workspace](https://www.datacamp.com/workspace). 

## License
See LICENSE for licensing details for this repository. 

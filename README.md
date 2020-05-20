# Visualizing-titanic-data-using-ggplot-R
This reporistory contains the visualizations of the famous Titanic problem dataset. Titanic dataset is also a good proxy for common business data for example, customer profile data. Simple lines of code in R and awareness of basic function and data visiualizations (eg. histogram, barchart etc.) can help to improve the understanding of data. This is the part of problem which is just 20 percent but useful over 80 percent of the time. 
> Alongside the visulaizations.R contains the code of implementation and the dataset titanic.csv can be downloaded from kaggle [here](https://www.kaggle.com/c/titanic/data). Hope these visualizations excite you about ggplot package in R.

The goal of the analysis is to explain the pattern of survival in the data


## Getting Started
The R studio need to have ggplot installed in it. If ggplot is not available then you can install by typing ```install.packages("ggplot2")``` in the R studio console. 

## Data Dictionary


| Variable  | Definition | Key |
| ------------- | ------------- | ------------- |
| survival  | Survival  | 0 = No, 1 = Yes  |
| pclass  | Ticket Class  | 1 = 1st, 2 = 2nd, 3 = 3rd  |
| sex  | Sex  | -  |
| Age  | Age in years  | -  |
| sibsp  | # of siblings/spouses aboard the titanic | -  |
| parch  | # of parents/children aboard the titanic | -  |
| ticket  | Ticket Number | -  |
| fare  | Passenger Fare | -  |
| cabin  | Cabin number | -  |
| embarked  | Port of embarkment | C = Cherbourg, Q = Queenstown, S = Southampton  |

## ggplot2
It is the de facto standard visualization package in R. It is used to design print quality graphics in seconds. It has a fine-grained control via an API (i.e., "the grammar") for layering graphical elements to build visualizations. 

Every visualization in ggplot2 is composed of the following:

* <b>Data</b>: The raw material of the visualization.
* <b>Layers</b>: What you see on the plots (e.g., points, lines, etc.)
* <b>Scales</b>: Maps the data to graphical output.
* <b>Coordinates</b>: The visualizations's perspective (e.g., a grid).
* <b>Faceting</b>: Provides "visual drill-down" into the data.
* <b>Themes</b>: Controls the details of the display (e.g., fonts).

Each ggplot2  visualization has three required components:

* <b>Data</b>: The raw material of the visualization
* <b>Aesthatics</b>: The mappings of your data to the visualization. For example, mapping the value of Titanic passenger ages to the y-axis of a graph.
* <b>Layers</b>: What you see on the plots (e.g., points, lines, etc.). These layers typically tke the form of a ggplot2 geom fucntion - for example, a simple scatter plot.

## Visualizations
### Survival Rate

As already mentioned 1 signifies the survival, and 0 signifies the perish.

<br>
<img src ="visualizations/Survival Rate_png.png">
<br>

It shows that 61.6 percent people perished on titanic and 38.4 people survived. 






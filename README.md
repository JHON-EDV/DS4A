# DS4A
# Understanding problematics in the vulnerable population of Metropolitan Area of Bucaramanga 

[![Dashboard|powerbi](https://www.ain.es/site/wp-content/themes/ain/imagen.php?idAccion=14623)](https://app.powerbi.com/view?r=eyJrIjoiZDQ3ZGQxYjAtY2ExMS00YTQ4LThhODItNTk3MjE4YjUyYWUzIiwidCI6IjQ0N2ViNTFjLWRlOGQtNGE2ZC1iNDVkLTAxNTYwN2RmYzk1MSJ9)

### _Social problem, Opportunity and Relevance_

In Bucaramanga, and its Metropolitan Area, there are different problems like organized crime, homicides, fighting between armed groups, illegal sale of psychotics, also, problems with the low opportunities and social stigmatization.

The problematic in general is: increase in the affectation of the rights of the vulnerable population in Bucaramanga and its metropolitan area. 

This issue is a concern of the mayor of Bucaramanga, however, the lack of a tool that allows to identify the critical points in the city represents a barrier to implement effective actions to mitigate the problems of the vulnerable population. 

Our solution will be identify the principal areas and risks situations for multiple populations in a georeferenced way, with statistical indicators

### _Why does this problem matter?_

The problems in Bucaramanga and its Metropolitan Area are violating the rights of civil society, generating a decrease in the quality of life of the population and, as a consequence, they only contribute more to the resurgence of violence. 

Therefore, this problem matters because identifying the areas with the greatest problems of insecurity and inequality can allow a diagnosis and, in turn, make decisions based on social and economic indices and improve the life quality of the metropolitan area of Bucaramanga.

## Features

- Interactive dashboard observe the classifications of people's vulnerabilities according to their population and territorial characteristics
- Interactive Dashboard with the classifications of the vulnerabilities of the people in the territory of Bucaramanga, the geolocation is carried out on average to the SISBEN classification.
- Interactive dashboard with the population and territorial characteristics of the people who have been given corrective measures by the police.
- Interactive dashboard population and territorial characteristics of people who have committed crimes in the municipality of Bucaramanga.
-  Interactive dashboard the population and territorial characteristics of the people who have died in the municipality of Bucaramanga.
-  Interactive dashboard with the corrective measures generated over time in the different neighborhoods are presented, a heat map is also associated where the most critical areas can be identified in red
- LSTM model based on corrective actions, with weekly time window



## Dash board 


## _Model_

To forecast the variables over time, the use of an LSTM network is proposed, which is a type of Recurrent Neural Network (RNN). LSTM models are capable of predicting a value from previous states given as inputs. Data processing, model and results are shown below.

Windows sizes for daily and weekly models are set in  60 days and 15 weeks respectively. 

Final data structure for train and test datasets is shown below. In our case, just one feature (events count) is considered.

# _Architecture_:

The initial proposed model is composed of five layers, the first 4 layers have also a dropout regularization layer with rate of 0.2  that helps to avoid overfitting and improve model performance. Model structure is shown in the following image.


| MAE | MSE |![equation](https://latex.codecogs.com/svg.image?r^{2}) |
| ------ | ------ |------ |
| 23.963 | 885.322| -0.131 |
# _Thanks to_:
- The entire team of DS4A Colombia.
- Mayor of Bucaramanga
- National Police

> "If I have seen further it is because I am sitting on the shoulders of giants"
> Sir Isaac Newton


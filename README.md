# (House Rent Prediction)
## by (Ben Goodness)


## Dataset

In this Dataset, we have information on almost 4700+ Houses/Apartments/Flats 
available for Rent with different parameters like BHK, Rent, Size, No. of 
Floors, Area Type, Area Locality, City, Furnishing Status, Type of Tenant Preferred,
No. of Bathrooms, Point of Contact. The dataset can be found in kaggle website 
[here](https://www.kaggle.com/datasets/iamsouravbanerjee/house-rent-prediction-dataset)
Before carrying out data exploration, we dropped 2 variables (No. of floors and
Area type), we also changed the datatypes and renamed the variables to a standard format.

## Summary of Findings

In the exploration, I found there was a strong relationship between rent of a house and
its size, The relationship is approximately linear between rent and size when they where 
plotted on a reg plot. I found a surprising result initially, i applied the xlim to look 
closer into the the data distribution, it appears that there's a non-linear increase of 
rent. Further analysis on categorical and norminal variables later revealed to us that 
other features like Bhk, City, Area Type and Point of Contact has positive reaction to 
Rent and is responsible for the non-linear increase of Rent.

## Key Insights for Presentation

For the presentation, I focus mainly on the influence which variables like size, bhk, 
bathroom, and city had on rent and and left out out most variables with weak interaction 
to rent. I start by introducing the rent variable, followed by the pattern in size distribution, 
then plot the transformed scatterplot.
Afterwards, I introduced the two categorical variables which were plotted in a boxplot showing 
their price distribution. Then i moved on to distributions of the norminal variables, I focused 
mainly on city variable sice it has the strongest reaction on rent. I started first by showing a 
facet distribution of city acros rent and size. Finally, showed a point plot of city and rent with 
two norminal variables that that had strong relationships with rent.
# Social Network Ads Prediction
Social network advertising, also social media targeting, is a group of terms that are used to describe forms of online advertising that focus on social networking services. One of the major benefits of this type of advertising is that advertisers can take advantage of the users’ demographic information and target their ads appropriately.Advantages are advertisers can reach users who are interested in their products, allows for detailed analysis and reporting, information gathered is real, not from statistical projections, does not access IP-addresses of the users.


## Data
For this study, we collected data from trusted website.
Data contains 5 columns.

__UserID__ - Each person has a unique ID from which we can identify the person uniquely.

__Gender__ - Person can male or female. This field is very important for our hypothesis.

__Age__ - Age of the person. Because our product can be useful to some ages only.

__EstimatedSalary__ - This column contains salary of a person as salary can affect the shopping of a person.

## Correlation Matrix

As we can see from the correlation matrix, our matrix's features has no highly correlated variables.Most correlated features are Purchase and Age(0.62)


![](https://github.com/KhazarHaydarli/Social-Network-Ads-Prediction/blob/main/figures/Correlation%20Matrix.png)

## Confusion Matrix

I have use KNearestNeighbor model.Model results without Hyperparameter is:

__Accuracy__ = 93.00

__F1_score__ = 89.23

![](https://github.com/KhazarHaydarli/Social-Network-Ads-Prediction/blob/main/figures/Confusion%20Matrix.png)

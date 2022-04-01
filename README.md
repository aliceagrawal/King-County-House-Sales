# King County House Sales 

![1622375_1](https://user-images.githubusercontent.com/100230332/161176285-2bf0605c-5fef-408d-9f5e-2384c5dd4b34.jpeg)

## Overview

Our team used multiple linear regression modeling to analyze house sales in King County, Washington.  

![thom-milkovic-skUTVJi8-jc-unsplash](https://user-images.githubusercontent.com/100230332/161176300-f064cb4d-de5d-46c5-8a48-93c4698f2cba.jpg)

## Business Problem

We were hired by King County Real Estate Inc. to create a model that will predict housing prices and help their employees be more effecient way pairing clients with their perfect house. 

![im-387931](https://user-images.githubusercontent.com/100230332/161176311-00d935e9-ec66-4310-ad70-9a59c222258a.jpeg)

## Data Understanding
We used the King County house sales data from 2014-2015 from Kaggle, and we also used data we found online that included zip codes and city names within King County, Washington. We merged the house sales data on zip codes so we could include city names, for more efficient grouping of sales.  Our data included the house condition, construction grade, view, and square feet of living area.

## Condition
Our model takes into account how well a house has been maintained. The difference in mean price between poor and fair isn't very high, but there is around a $150,000 expected increase between fair and average. Also there is a $50,000 expected increase between good and very good. Possible buyers are able to use this information and choose between getting a house for less and remodeling later or buying a house that will be in a great condition to start with.

![Conditions_bar](https://user-images.githubusercontent.com/100230332/161277147-138a565f-c666-4516-a8ef-65325ba72570.jpeg)


## Grade
We included grade or quality of construction, into our model because we can see an exponential increase in mean prices as the grade increases, especially once you get above a grade 9.  A grade 9 has "better architectural design with extra interior and exterior design and quality." according to the King County Assessor website.

![Grade_bar](https://user-images.githubusercontent.com/100230332/161176273-312ad9bf-9e26-4fbf-a705-1f2abb11b64c.png)

## View
Our model accounts for the quality of the view from the house and property. Having an Excellent view can nearly double the mean price of a house when compared with a house that has an Average or Good view.
![View_bar](https://user-images.githubusercontent.com/100230332/161176280-277ed7ad-90cc-4e2c-9997-f91d36c3d79c.png)


## City
Our model includes cities as key predictors of housing prices. Houses prices vary according to the city they are in. Living within Seattle’s city limits gives you the options for a lower priced and there are also many other suburbs that have low priced options, like Renton, Bellevue, and Kirkland. Cities such as Medina, Fall City, and Black Diamond all have a mean price close to, or above, 1 million dollars.

![City_bar](https://user-images.githubusercontent.com/100230332/161183225-d9c063b6-53db-4a5c-b341-edc1c7d116e1.png)



## Conclusions
1. We would recommend that clients with a lower budget, find houses that are in fair condition with a grade that is low or fair. We would also suggest find a view that is Average or Good.

2. We would recommend that clients with a higher budget look for a house in Medina that is in Excellent condition and has an excellent view, however if view is not as important to them, they can save a lot of money by purchasing a house that has an average or good view, rather than an excellent view.  They should also search for houses that have more bathrooms per bedrooms.

3. Finally for clients who are looking to sell their houses, renovations that increase the square footage of their living area, increase the number of bathrooms per bedrooms, and improve the condition and construction grade of their house, will all see a substantially increase in the value of their home.


## Next Steps
Further analysis may prove beneficial in these areas:
1. Fixing the waterfront data to better reflect whether a house is on the water.
2. Finding data on School District Ratings within King County.
3. Finding data on Crime Statistics of cities within King County.


![cover-26-1255x600](https://user-images.githubusercontent.com/100230332/161176329-2b06cf07-8d67-42dd-ba2d-29dcea4a057b.jpeg)







 ├── data
 ├── images
 ├── IndividualNotebooks
 │       ├── Alice's Workspace
 │       ├── Marshall's Workspace
 │       └── Jordan's Workspace
 │
 ├── gitignore
 ├── King_County_final.ipynb
 ├── King County Housing Data Presentation.pdf
 └── README.md

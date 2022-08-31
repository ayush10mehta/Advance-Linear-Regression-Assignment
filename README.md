#  Advance Linear Regression Assignment
> In order to predict the actual prices of the houses, we had to create a linear regression model using regularization techniques for this programming project. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- A bike-sharing system is a service that makes bikes available to people for short-term, shared use that can be paid for or provided for free. Many bike share programmes enable users to pick up a bike from a "dock," which is typically computer-controlled and where they enter their payment details to have the bike unlocked. Then, you can return this bike to a different system-affiliated dock.

### Problem Statement

- The ongoing Corona pandemic has recently caused a US bike-sharing company, BoomBikes, to experience significant drops in income. In the current market environment, it is extremely difficult for the organisation to remain viable. It has therefore made the conscious decision to develop a business plan that will enable it to increase revenue as soon as the ongoing lockdown ends and the economy returns to a healthy state.

- BoomBikes hopes to understand how people will feel about shared bikes when the current Covid-19-related nationwide quarantine situation ends in this effort. They have planned this in order to differentiate themselves from other service providers and be ready to meet people's requirements when everything improves.

### Business Goals
- With the available independent variables, we must model the demand for shared bikes. The management will use it to determine precisely how the needs change with changing features. They can adjust their business approach in accordance with demand levels and client expectations. The model will also help management better grasp the dynamics of demand in a new market.

### About the Data
- The data set used is the train.csv data set. It have 1460 rows and 81 columns. Explaining the columns which has been most used for the analysis and modeling purposes.

1. MSSubClass: Identifies the type of dwelling involved in the sale.
2. MSZoning: Identifies the general zoning classification of the sale.
3. LotFrontage: Linear feet of street connected to property
4. LotArea: Lot size in square feet
5. Street: Type of road access to property
6. Alley: Type of alley access to property
7. LotShape: General shape of property
       
8. LandContour: Flatness of the property
9. LotConfig: Lot configuration
	
10. LandSlope: Slope of property
	
11. Neighborhood: Physical locations within Ames city limits
			
12. Condition1: Proximity to various conditions
	
13. Condition2: Proximity to various conditions (if more than one is present)
	
14. BldgType: Type of dwelling
	
15. HouseStyle: Style of dwelling
	
16. OverallCond: Rates the overall condition of the house
		
17. YearBuilt: Original construction date

18. YearRemodAdd: Remodel date (same as construction date if no remodeling or additions)

19. RoofStyle: Type of roof
		
20. RoofMatl: Roof material
		
21. Exterior1st: Exterior covering on house
	
22. Exterior2nd: Exterior covering on house (if more than one material)

	
23. MasVnrType: Masonry veneer type
	
MasVnrArea: Masonry veneer area in square feet

ExterQual: Evaluates the quality of the material on the exterior 
		
ExterCond: Evaluates the present condition of the material on the exterior
		
     
		
Foundation: Type of foundation
		
		
BsmtQual: Evaluates the height of the basement

		
BsmtCond: Evaluates the general condition of the basement
BsmtExposure: Refers to walkout or garden level walls
	
BsmtFinType1: Rating of basement finished area

BsmtFinSF1: Type 1 finished square feet

BsmtFinType2: Rating of basement finished area (if multiple types)


BsmtFinSF2: Type 2 finished square feet

BsmtUnfSF: Unfinished square feet of basement area

TotalBsmtSF: Total square feet of basement area

Heating: Type of heating
		
		
HeatingQC: Heating quality and condition
		
CentralAir: Central air conditioning
		
Electrical: Electrical system

		
1stFlrSF: First Floor square feet
 
2ndFlrSF: Second floor square feet

LowQualFinSF: Low quality finished square feet (all floors)

GrLivArea: Above grade (ground) living area square feet

BsmtFullBath: Basement full bathrooms

BsmtHalfBath: Basement half bathrooms

FullBath: Full bathrooms above grade

HalfBath: Half baths above grade

Bedroom: Bedrooms above grade (does NOT include basement bedrooms)

Kitchen: Kitchens above grade

KitchenQual: Kitchen quality

       	
TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)

Functional: Home functionality (Assume typical unless deductions are warranted)

		
Fireplaces: Number of fireplaces

FireplaceQu: Fireplace quality
		
GarageType: Garage location
		
GarageYrBlt: Year garage was built
		
GarageFinish: Interior finish of the garage
		
GarageCars: Size of garage in car capacity

GarageArea: Size of garage in square feet

GarageQual: Garage quality
		
GarageCond: Garage condition
		
PavedDrive: Paved driveway
		
WoodDeckSF: Wood deck area in square feet

OpenPorchSF: Open porch area in square feet

EnclosedPorch: Enclosed porch area in square feet

3SsnPorch: Three season porch area in square feet

ScreenPorch: Screen porch area in square feet

PoolArea: Pool area in square feet

PoolQC: Pool quality
		
		
Fence: Fence quality
		
	
MiscFeature: Miscellaneous feature not covered in other categories
		
     
MiscVal: $Value of miscellaneous feature

MoSold: Month Sold (MM)

YrSold: Year Sold (YYYY)

SaleType: Type of sale
		
SaleCondition: Condition of sale
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Flow Diagram
![Flow chart](https://github.com/ayush10mehta/Advance-Linear-Regression-Assignment/blob/main/Flow.png?raw=true)

## Conclusions
1. Optimum value for lasso regression: {'alpha': 62.06206206206207}
2. Optimum value for ridge regression: {'alpha': 8.0}
3. The r2_score of lasso is slightly higher than ridge for the test dataset so we will choose lasso regression to solve this problem.
 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy version - 1.22.3
- pandas version - 1.4.2
- matplotlib version - 3.3.2
- seaborn version - 0.11.2
- missingno version - 0.4.2
- plotly version - 5.1.0
- scikit-learn - 0.24.1
- category-encoders - 2.2.2
- statsmodels - 0.14.0
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- We have taken the references of data computation methods from some of the python libraries.
1. Numpy: https://numpy.org
2. Pandas: https://pandas.pydata.org
- We have taken the references of data visualization from some of the python libraries.
1. Plotly: https://plotly.com
2. Seaborn: https://seaborn.pydata.org
3. Matplotlib: https://matplotlib.org
- We have taken the references of data modeling from some of the python libraries.
1. scikit-learn: https://scikit-learn.org/stable/
2. category-encoders: https://contrib.scikit-learn.org/category_encoders/
3. statsmodels: https://www.statsmodels.org/stable/index.html 


## Contact
Created by [@ayush10mehta] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

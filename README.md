#  Advance Linear Regression Assignment
> In order to predict the actual prices of the houses, we had to create a linear regression model using regularization techniques for this programming project. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- Surprise Housing, a US-based housing company, has made the decision to enter the Australian market. The business buys homes for less than their actual value and sells them for more using data analytics. The business has gathered a set of data from Australian home sales for the same objective. The CSV file below contains the data.In order to enter the market, the company is looking at potential properties to purchase. To determine the actual value of the potential properties and whether to invest in them or not, you must construct a regression model using regularisation.

### Business Goals
- Modeling the cost of homes using the relevant independent variables is required. This model will then be used by the management to understand how exactly the prices fluctuate with the factors. As a result, they can influence the company's strategy and concentrate on areas that will provide large returns. The tool will also help management better understand how prices change in a new market.

### About the Data
- The data set used is the train.csv data set. It have 1460 rows and 81 columns. Explaining the columns which has been most used for the analysis and modeling purposes.

MSSubClass: Identifies the type of dwelling involved in the sale.
MSZoning: Identifies the general zoning classification of the sale.
LotFrontage: Linear feet of street connected to property
LotArea: Lot size in square feet
Street: Type of road access to property
Alley: Type of alley access to property
LotShape: General shape of property
       
LandContour: Flatness of the property
LotConfig: Lot configuration
	
LandSlope: Slope of property
	
Neighborhood: Physical locations within Ames city limits
			
Condition1: Proximity to various conditions
	
Condition2: Proximity to various conditions (if more than one is present)
	
BldgType: Type of dwelling
	
HouseStyle: Style of dwelling
	
OverallCond: Rates the overall condition of the house
		
YearBuilt: Original construction date

YearRemodAdd: Remodel date (same as construction date if no remodeling or additions)

RoofStyle: Type of roof
		
RoofMatl: Roof material
		
Exterior1st: Exterior covering on house
	
Exterior2nd: Exterior covering on house (if more than one material)

	
MasVnrType: Masonry veneer type
	
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

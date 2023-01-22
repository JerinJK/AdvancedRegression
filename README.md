# Advanced Regression
> US Based Company  uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. This project is to help then analyse the features contributing to price of houses based on previous data.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
US Based Company  uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. This project is to help then analyse the features contributing to price of houses based on previous data. Data is available based on different features which are available in house.
  MSSubClass: Identifies the type of dwelling involved in the sale.	
  MSZoning: Identifies the general zoning classification of the sale.
  LotFrontage: Linear feet of street connected to property
  LotArea: Lot size in square feet
  Street: Type of road access to property
  Alley: Type of alley access to property
  LotShape: General shape of property     
  LandContour: Flatness of the property
  Utilities: Type of utilities available
	LotConfig: Lot configuration
  LandSlope: Slope of property
	Neighborhood: Physical locations within Ames city limits  		
  Condition1: Proximity to various conditions
  Condition2: Proximity to various conditions (if more than one is present)
	BldgType: Type of dwelling
	HouseStyle: Style of dwelling
	OverallQual: Rates the overall material and finish of the house
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
 
 
## Technologies Used
   - Python with numpy , pandas, Seaborn, matplotlib, statsmodels, sklearn liraries
   - Linear Regression Concepts
   
## Steps followed
   - Data understanding 
   - Removing unnecessary columns , renaming and also taking care of categorical variables.
   - Divide data into training and test set.
   - Scaling of data
   - Use Ridge and Lasso
   - R2 score
   - Run the test on Test dataset
   - Evaluate the model
   - Check for Assumptions  - 
   - Solution to Questions   - 
   - Conclusion
   
## Conclusions
- Factors affecting the price of building  :
  GrLivArea              		- Above grade (ground) living area square feet
  OverallQual            		- Rates the overall material and finish of the house
  LotArea                		- Lot size in square feet
  GarageCars             		- Size of garage in car capacity
  OverallCond            		- Rates the overall condition of the house
  Old_Yr                 		- derived variable from when the house is build
  MSSubClass             		- Identifies the type of dwelling involved in the sale
  GarageCExterior1stars 		- Exterior covering on house
  Neighborhood	                  	- Physical locations within Ames city limits
  TotRmsAbvGrd     	              - Total rooms above grade
  BsmtFullBath       		- Basement full bathrooms
  FullBath           			- Full bathrooms above grade
  2ndFlrSF          			- Second floor square feet
 LotFrontage	       	 - Linear feet of street connected to property



## Technologies Used
- Python with numpy , pandas, Seaborn, matplotlib, statsmodels, sklearn liraries


## Contact
- https://github.com/JerinJK


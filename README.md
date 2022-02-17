# sales-predictions
This project aimed to understand the influence of the type of products and outlets' location, size, and type on the outlet sales. It was applied a methodology focused on two critical aspects:
a. Describing the influence of different variables on the outlet sales graphically.
b. Applying machine learning algorithms to identify the most important variables affecting the outlet sales. 
# Summary of important results
A. Graphical description of the influence of important variables on outlet sales
![image](https://user-images.githubusercontent.com/96077675/154581416-ab0174a9-0e86-4327-bdc7-cd6c95121887.png)

## Figure 1. Outlet sales by item type
The median of the outlet sales by product is around of 2000 USD.

![image](https://user-images.githubusercontent.com/96077675/154581614-98200a97-aa8d-4074-a04a-38398e712d64.png)

## Figure 2: Item outlet sales by item type and fat content
Households, snacks, and fruits & vegetables are the more sold items. It is important to note that low fat content products are preferred by customers.

![image](https://user-images.githubusercontent.com/96077675/154581936-f885c13f-8197-4581-b5f9-1201840d103f.png)

## Figure 3: Item outlet sales by outlet size and location
Medium size and tier 3 outlets gather the most of the outlet sales. 

![image](https://user-images.githubusercontent.com/96077675/154582164-ff3efa2a-42bc-4788-826f-119129b08be4.png)

## Figure 4: Item outlet sales by outlet size and type
Medium size and supermarket type 1 outlets gather the most of the outlet sales.

B. Applying machine learning algorithms to identify the most important variables affecting the outlet sales. 
![image](https://user-images.githubusercontent.com/96077675/154582593-f216109f-9a61-48c6-bee4-b2a496ff16db.png)

## Figure 5: Correlation matrix
The correlation matrix reveals that there are no correlation among variables, with the exception of Item MRP on item outlet sales. 

After the database preprocessing, data were fitted to Linear Regression, k-NN regression, and Random Forest Regression models to discover the influence of several essential variables on the outlet sales. To compare the models successfully, cross-validation (with cv=10) was applied. The following table shows the results obtained: 

## Table 1: Scores meand and standar deviation for ML models
![image](https://user-images.githubusercontent.com/96077675/154583741-ed2e2d72-1a6b-40d3-a5d0-540135b5901e.png)



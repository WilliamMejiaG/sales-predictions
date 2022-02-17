# Sales predictions
This project aimed to understand the influence of the type of products and outlets' location, size, and type on the outlet sales. It was applied a methodology focused on two critical aspects: a) Describing the influence of different variables on the outlet sales graphically, and b) Applying machine learning algorithms to identify the most important variables affecting the outlet sales. 
# Summary of important results
## A. Graphical description of the influence of important variables on outlet sales
![image](https://user-images.githubusercontent.com/96077675/154581416-ab0174a9-0e86-4327-bdc7-cd6c95121887.png)

### Figure 1. Outlet sales by item type
The median of the outlet sales by product is around of 2000 USD.

![image](https://user-images.githubusercontent.com/96077675/154581614-98200a97-aa8d-4074-a04a-38398e712d64.png)

### Figure 2: Item outlet sales by item type and fat content
Households, snacks, and fruits & vegetables are the more sold items. It is important to note that customers prefer low-fat content products.

![image](https://user-images.githubusercontent.com/96077675/154581936-f885c13f-8197-4581-b5f9-1201840d103f.png)

### Figure 3: Item outlet sales by outlet size and location
Medium size and tier 3 outlets gather the most of the outlet sales. 

![image](https://user-images.githubusercontent.com/96077675/154582164-ff3efa2a-42bc-4788-826f-119129b08be4.png)

### Figure 4: Item outlet sales by outlet size and type
Medium size and supermarket type 1 outlets gather the most of the outlet sales.

## B. Applying machine learning algorithms to identify the most important variables affecting the outlet sales. 
![image](https://user-images.githubusercontent.com/96077675/154582593-f216109f-9a61-48c6-bee4-b2a496ff16db.png)

### Figure 5: Correlation matrix
The correlation matrix reveals that there are no correlation among variables, with the exception of Item MRP on item outlet sales. 

After the database preprocessing, data were fitted to Linear Regression, k-NN regression, and Random Forest Regression models to discover the influence of several essential variables on the outlet sales. To compare the models successfully, cross-validation (with cv=10) was applied. The following table shows the results obtained: 

### Table 1: Scores mean and standar deviation for ML models
![image](https://user-images.githubusercontent.com/96077675/154583741-ed2e2d72-1a6b-40d3-a5d0-540135b5901e.png)

Table 1 shows that to predict the item outlet sales accurately, Linear Regression and Random Forest Regression should be applied. This is showed graphically in Figure 6:

![image](https://user-images.githubusercontent.com/96077675/154585190-e7814048-5f4c-4f42-91dc-35ec433145eb.png)

### Figure 6: Distribution of the scores of the tested ML models

![image](https://user-images.githubusercontent.com/96077675/154585339-3ad90b1e-6e4d-44e8-86ff-d5750cc0618d.png)

### Figure 7: Linear regression results

Figure 7 shows that the item MRP follows a linear tendency with outlet sales, as was expected. 

Table 2. Features importance as classified by random forest algorithm
![image](https://user-images.githubusercontent.com/96077675/154585621-7b081b98-3d92-4ddd-b705-2e8470f8a4f4.png)

### Table 2 shows the features importance as classified by random forest algorithm. As expected, item MRP was recognized as the most influential.

# Conclusions
### It is essential to prioritize the sales of snacks, households, and fruits & vegetables to increase the outlet sales. 
### Medium size, tier 3, and type 1 supermarkets are essential to raising the outlet sales. 
### Item MRP is proportional to outlet sales, and it is the most influential variable to predict outlet sales.




# Outlet_sales_predictions

## Author: Akinde Kadjo

![retail-products](https://user-images.githubusercontent.com/111167621/191670964-20c7c4c8-4664-4cef-8bf1-d240de64be4e.jpg)
Image taken from [displays2go.com](https://www.displays2go.com/Industry/Retail-Fixtures-Selling-Merchandise-Brick-Mortar-Stores-67)

## Introduction and Goals
For businesses such as retails, it is important for the stakeholders to have a better understanding of the factors improving their revenues in order to maximize their growth. And predicting sales plays a signifcant role in this. With a decent prediction model,the proper decisions will be made as of what items will likely sell more (to prevent unused inventory) or what features need to be enhanced to increase sales.
In this project the goal is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales. 

## Data Info
The data was provided from a Class Assignment.


## Methods Used
The languague used fo this Project is Python in a Collaboratory environement.
Data cleaning prtotocol consisted of checking for duplicate (then removing them), checking for the presence of missing data, and fixing inconsistent data.
Scikit libraries were used for machine learning, such as preprocessor and Simple Imputer. Predictions were done with both linear regression model and an optimized Random forest model.

## Interpretation
A heatmap was produced to assess the numerical features primarily driving the outlet sales. As seen in the figure below, the positive corelation of 0.57 with the item MRP is a clear indicator of its impact on the Item Outlet sales. Item visibility shows a faint correlation, however Establishment year and Item weight in no ways are driving factors of the overal sales.

![image](https://user-images.githubusercontent.com/111167621/191671527-53768e31-d3a5-414a-86c3-10565e06d8e7.png)



The histogram below gives us an overview of the distributions of various features such as outlet sales, item MRPs and item visibilities in our dataset. From the figure below it seems as thought: items that bring in a lot of sales are a lot less than items that don't. The item MRP is somehow evenly distributed. Also, a lot of items tends to have lower visibility.

![image](https://user-images.githubusercontent.com/111167621/191872576-e8f96aba-ac1e-40a3-85dd-9ae163066671.png)



The barplots below shows us that factors such as Item Type, Item MRP, Outlet Size, Outlet Location Type, and Outlet Type have unique values that may somehow contribute to the outlet sales and therefore may be good prediction features.

On the other end, Item Fat content doesn't seem to play much of a role in the outlet sales, both the low fat items as well as the regular items contribute about equally.

![image](https://user-images.githubusercontent.com/111167621/191671606-6f9ff616-b69d-412c-9678-d01967d75300.png)

After processing the data through both linear regression and Random Forest models, the predictions shown below were achieved. The Random Forest model performed a lot beter than the linear regression model.
![image](https://user-images.githubusercontent.com/111167621/191884193-d5d22cc8-7fc0-4a6e-adf6-865119feec78.png)

## Conclusion
Overall a moderate prediction was achived using the random forest model. Potentially, there are unknown features that may contribute to improve the model but that have not been reported.

### For further information
For any additional questions, please contact akindeflo@gmail.com

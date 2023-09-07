# Creatin_ML_Model_For_Predcition_of_SalesQuantities
In this project. I needed to implement an ML model to accurately predict the sales quantities called "net_quantity".

## DATASET
1. The dataset contains both numeric and categorical attributes.
2. The attribute called "net_quantity" is the target variable and is a continuous numeric
variable.

### Hint: “net_quantity” shows the amount of sales in previous periods.

## MODEL BUILDING

1. The model should work for each unique product code and generate predictions for period_id 1 for which net_quantity is "NaN".
'For the dataset given below, for example, the created model first should be trained on the
dataset its product_code=21WW23074MA (period_id=2,3,4,5,6,7,8,9,10,11,12,13,14,1,2) and
should create a prediction for the same dataset its product_code=21WW23074MA and period
id is 1. Then, the same process should be repeated for product_code=22SW35094ST'.

2. If the period length for a product_code is less than 10, the model will not run for this
product_code and will move to the next product_code.
3. You should split the dataset generated for each product_code with prediod_id is different
than 1 into training and testing.

4. The performance of the model will be measured separately on the training and test set and
the R2 and MSE score.

Finally, the predictions can be float values. However, since our target value represents the sales
amount, float values cannot be used as they are. You are expected to find a creative solution
to this situation.


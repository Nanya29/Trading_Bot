# Trading_Bot

## Original result
      precision    recall  f1-score   support

        -1.0       0.43      0.04      0.07      1804
         1.0       0.56      0.96      0.71      2288

    accuracy                           0.55      4092
   macro avg       0.49      0.50      0.39      4092
weighted avg       0.50      0.55      0.43      4092



## Altenate- 
### Step 1- Tune the training algorithm by adjusting the size of the training dataset. 
###What impact resulted from increasing or decreasing the training window?
*Answer- Decreasing the training window reduced the recall and f1-score to nearly zero


### Step 2: Tune the trading algorithm by adjusting the SMA input features. 
###Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?
*Answer- The data size



###increasing ending period to 7 months for the training data and ### Setting short and long window to 20 and 250

         precision    recall  f1-score   support

        -1.0       0.44      0.71      0.54      1544
         1.0       0.57      0.30      0.39      2004

    accuracy                           0.48      3548
   macro avg       0.50      0.50      0.47      3548
weighted avg       0.51      0.48      0.46      3548


###increasing ending period to 3 months for the training data and ### Setting short and long window to 20 and 250
         precision    recall  f1-score   support

        -1.0       0.50      0.07      0.12      1718
         1.0       0.56      0.94      0.71      2194

    accuracy                           0.56      3912
   macro avg       0.53      0.51      0.41      3912
weighted avg       0.53      0.56      0.45      3912


###increasing ending period to 3 months for the training data and ### Setting short and long window to 15 and 180

           precision    recall  f1-score   support

        -1.0       0.48      0.05      0.09      1732
         1.0       0.56      0.96      0.71      2211

    accuracy                           0.56      3943
   macro avg       0.52      0.50      0.40      3943
weighted avg       0.53      0.56      0.44      3943




### Step 3: Choose the set of parameters that best improved the trading algorithm returns. 
###increasing ending period to 4 months for the training data and ### Setting short and long window to 15 and 180
              precision    recall  f1-score   support

        -1.0       0.49      0.07      0.12      1707
         1.0       0.56      0.94      0.71      2173

    accuracy                           0.56      3880
   macro avg       0.52      0.51      0.41      3880
weighted avg       0.53      0.56      0.45      3880

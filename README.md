# Customer-Coupon-Acceptance

* The goal of the project is to find "if the customer accepts the coupon or not". The observation while doing the analysis are present in the below notebook.

         [Jupyter Notebook](https://github.com/kjvk/Customer-Coupon-Acceptance/blob/main/prompt.ipynb)

* There are certain columns like below, which doesn't have proper description/information or data. Also they are not required for the current targeted analysis, hence removed.
  
         * car
  
         * toCoupon_GEQ5min
  
         * toCoupon_GEQ15min
  
         * toCoupon_GEQ25mi columns

* Below are the columns which have missing values, the missing values were replaced with the Mode imputation mechanishm. This mechanism will replace the missing values with the more frequent 
  occuring data.
  
         * Car
  
         * Bar
  
         * CoffeeHouse
  
         * CarryAway
  
         * RestaurantLessThan20
  
         * Restaurant20To50
  
*     


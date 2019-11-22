# Installation 

- Run the following commands in your terminal 

> - git clone https://github.com/a-madhukar/products-test.git
> - cd products-test
> - npm install 


# Scenario 

A backend endpoint returns an array of products. However, some of these products have empty details. The name may be empty, the price might be 0, or the category is blank. 

# Problem

Implement a method that calculates the total value of products (total price) where there are no missing, invalid, or empty values. So no empty strings, null values, and 0 values. 

> - Go to app.js 
> - Find the method called totalSumOfProducts
> - implement your solution here

The method has already been provided, you just need to implement the logic for it. 

# Testing 

Once you've satisfied with your code, just run **npm run test**, and it should tell you if your code works. 

Make sure at least one of the test passes. :) 

# Bonus Problem

At any given point of time, your backend developer might change the keys returned in the response. So instead of name, it could be item_name or title, etc. 

Implement a method that dynamically checks the key pair values of every object, and calculates the total sum provided it doesn't have any empty fields. 

Note: There will be only 1 integer field returned in the object. You can assume that this would be the price.
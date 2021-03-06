![alt text](https://media-assets-02.thedrum.com/cache/images/thedrum-prod/s3-news-tmp-90538-wish_e-commerce--2x1--940.png)

# Broken Wish? Gauging the Effectiveness of Wish's Product Promotion

## Blog Version


# Summary
My name is Christian Rios-Chambi and I am a Data Analyst working for the e-commerce company Wish. My presentation will be on gauging the effectiveness of Wish’s product promotions. Wish is an American online e-commerce company. As of 2019 Wish is the third-biggest e-commerce marketplace in the United States by sales. So what makes Wish unique from its competitors? Instead of using the traditional search bar format, customers use tags (keywords) to find the products they are looking for. Also, a wide variety of merchants can list their products on Wish and can sell directly to the consumer (at high discount rates), avoiding the preverbal middlemen. There are three main product promotions that I want to investigate and I want to see if I can predict units sold using the tag count of the product.

## **Here are the promotions** 
- **Ad boosts**
- **Product badges**
- **Tag count (the number of keyword associations to a product)**



**Ad Boost** 
- *Ad Boost is the native advertising platform of Wish Marketplace. It is a PAID SERVICE for merchants*

**Product badges** 
- *There are three product badges offered on the Wish Platform.*

**Product Quality Badge:** 
- *it can only be given to a product that has high ratings, high sales, and a low refund ratio.*

**Fast Shipping Badge:** 
- *It is given to a product that can be rapidly shipped to the customer.*

**Local Product Badge:** 
- *The product was made in the country of the customer.*

**Tag Count** 
- *Merchants set which tags and how many tags they want to be associated with their products.*

# Objectives
- Are ad boosts increasing product revenue?
- Are product badges increasing product revenue?
- Does the tag count have an effect on product revenue?
- Can we predict the units sold of a product by just looking at its tag count?

# Project Steps & Further Questions:

## Data Cleaning:

- Remove duplicates or records with missing or mismatched values.
- Removing unnecessary columns. 
- Replacing certain null values with appropriate zero values.

## Data Wrangling:

- Created new columns for better analysis.
- Creating functions to help label data.
- Creating Visualizations.

## Ad Boosts:

- 584 products with ad boosts, 757 products without ad boosts.
- $37,400 average product revenue for products with ad boosts, $40,313 average product revenue for products without ad boosts.
- *Unsuccessful Products* = 45% of products use ad boosts, *Successful Products* = 41% of products use ad boosts.

## Product Badges:
- 10% of products have a product badge.
- Products with badges generate 34% more average revenue per product compared to products without badges.

## Tag Count:
- Most of the products have between 13 to 19 tags, 16 being the most popular number of tags.
- Products that have a high tag count (29, 34, 37, 41) are generating a higher average product revenue than the popular 13-19 tag range. 

## Linear Regression Model - Predicting Units Sold using Tag Count:
- I wanted to see if a linear regression model could be created in order to predict the number of units sold of a product.
- Unfortunately due to the way the units sold were inputted in the dataset, there was no way to create an effective model to predict units sold.
- A more robust data set is needed for this model creation.

## Recommendations and Next Steps:
- The Ad boost service needs to be investigated even further.
- Inform the merchants on Wish about the effectiveness of product badges.
- Run some tests to see if limiting the number of tag words per product would have any effect on sales.
- More robust data is needed to implement an appropriate prediction model for units sold.

# Contact Information 
- **Name:** Christian Rios-Chambi
- **Email:** crioschambi@gmail.com
- **LinkedIn:** linkedin.com/in/christian-rios-chambi/
- **Github:** github.com/criosch1
- **Website:** crioschambi.com

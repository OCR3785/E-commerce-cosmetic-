# E-commerce-cosmetic-
**About this project:**

The dataset (E-commerce cosmetic dataset) was chosen because we are both business experts in buying cosmetics online and are familiar with all its features. The dataset also meets the project's requirements with over 10K rows and 15 columns.
We had an opening session in which we chose the dataset and set our main business question. Following this, we had a few more working sessions to progress on the project.

This is how we splited the tasks between us:
  
*   What is our data base about. How can it help to gain profit, what are the problems, what did we test, reading litreture review and what we found / Or
*   Import the data
*   Overall look (shape, info, describe)
*   Clean the data:
      *Show columns with missing data, rating column type change / Gil  
*   Statitics:
*    2-3 descriptive graphs (histograms etc.) /Or
*    Finding outliers /Gil
*    Investigating the tendency between 2 features (2-3 graphs that display columns tendency with number of ratrings) / Gil
*    Exploring the correlation between price and number of ratings /Or

**Here is a link to our database:**
https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop

---
This database deals with e-commerce products from different websites for Indian customers. Each row represents a product.
**Our main business question** is how the price of a product influences the number of ratings for that particular product. This is important for website managers and product suppliers to know because a lower number of ratings overall can reduce the attractiveness and perceived validation of the product by new buyers, affecting their decision to purchase the product (Baymard Institute 2024). Hence,  we predict that lower-priced products will have a higher number of ratings and vice versa. Yet, other factors are in play as well and produt category is also important for rating (Lindgren 2021).

**Procedure**
To investigate how pricing influences the number of ratings, we first familiarized ourselves with the main variables, types, number of observations for each variable, sample size and outliers. We also consider the tendency of the product brand and the category of the cosmetic solution (e.g., face, body, eyes, etc.) on the number of ratings. We then cleaned the data by handling missing values. We applied descriptive statistics to all variables of interest, in tables and graphs. Finally, we calculated the correlation between the variables of interest.

Our **main findings** show that most bought products are low-priced and have a small number of ratings (less than 100 voters). In addition, most products that received a relatively high number of ratings are face and body products associated with the Maybelline, Lakmi and Swiss Beauty, REVLON and Clinique brands.

Finally, we found a weak and statistically significant negative correlation between price and the number of ratings, which aligns with the literature review. However, the small effect size suggests that other variables have a stronger effect on the number of ratings. Further investigation should apply multiple regression to investigate the relative effect size of other variables that influence the number of ratings, such as brand and category.





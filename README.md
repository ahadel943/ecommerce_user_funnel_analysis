# E-Commerce User Funnel Analysis

# Introduction

In the fast-paced world of e-commerce, understanding the customer journey is crucial for optimizing user experience and maximizing conversions. User funnel analysis plays a pivotal role in identifying where potential customers drop off in their journey from initial engagement to making a purchase. This project aims to delve into the intricacies of the e-commerce user funnel, providing insights that can drive strategic improvements and boost overall performance.

# Project Overview

This project involves the analysis of user interactions and behaviors across various stages of the e-commerce funnel, from initial website visits to final purchases.

## Tools used
1) Microsoft Power BI for charts and visuals.
2) Power BI DAX for calcualting KPIs and metrics.

## Business Questions and Tasks

1) What are the total users count ?
2) What are total count of users for each stage ?
3) What is the conversion rate ?
4) What is the conversion rate for each stage ?
5) What is the drop-off rate ?
5) What is the drop-off rate for each stage ?

## Data Features

| Column | Count | Type |
| ------ | ----- | --------- |
| User_ID | 17,175 | TEXT |
| Stage | 17,175 | TEXT |
| Conversion | 17,175 | BOOL |

## Data cleaning and preparatrion

After cleaning, preparing and understanding the data found the following notes

1) The dataset includes **17,175** records.
2) The dataset contains **3** features.
3) No missing values.
4) KPIs and Metrics calculated

| Column | Date Type | KPI Type  |
| ------ | --------- | --------- |
| _total_users | NUMBER | **WEB TRAFFIC KPI** |
| _homepage_users | NUMBER | **WEB TRAFFIC KPI** |
| _productpage_users | NUMBER | **WEB TRAFFIC KPI** |
| _cart_users | NUMBER | **WEB TRAFFIC KPI** |
| _checkout_users | NUMBER | **WEB TRAFFIC KPI** |
| _purchase_users | NUMBER | **SALES KPI** |
| _conversion_rate | PERCENTAGE | **USER BEHAVIOR KPI** |
| _drop_off_rate | PERCENTAGE | **USER BEHAVIOR KPI** |
| _homepage_to_productpage_cr | PERCENTAGE | **USER BEHAVIOR KPI** |
| _productpage_to_cart_cr | PERCENTAGE | **USER BEHAVIOR KPI** |
| _cart_to_checkout_cr | PERCENTAGE | **USER BEHAVIOR KPI** |
| _checkout_to_purchase_cr | PERCENTAGE | **USER BEHAVIOR KPI** |
| _homepage_to_productpage_do | PERCENTAGE | **USER BEHAVIOR KPI** |
| _productpage_to_cart_do | PERCENTAGE | **USER BEHAVIOR KPI** |
| _cart_to_checkout_do | PERCENTAGE | **USER BEHAVIOR KPI** |
| _checkout_to_purchase_do | PERCENTAGE | **USER BEHAVIOR KPI** |


## Conclusions
1) By using power bi DAX we uncovered the following KPIs values:
    * _total_users: 17,175 users.
    * _homepage_users: 10,000 users.
    * _productpage_users: 5,000 users.
    * _cart_users: 1,500 users.
    * _checkout_users: 450 users.
    * _purchase_users: 225 users.
    * _conversion_rate: 2.25%.
    * _drop_off_rate: 97.75%.
    * _homepage_to_productpage_cr: 50.00%.
    * _productpage_to_cart_cr: 30.00%.
    * _cart_to_checkout_cr: 30.00%.
    * _checkout_to_purchase_cr: 50.00%.
    * _homepage_to_productpage_do: 50.00%.
    * _productpage_to_cart_do: 70.00%.
    * _cart_to_checkout_do: 70.00%.
    * _checkout_to_purchase_do: 50.00%.

2) Based on the calculated KPIs and conversion/drop-off rates for each stage of the sales funnel, the following insights were found:
    * The overall **conversion rate** of **2.25%** indicates that a small fraction of users who start at the homepage end up making a purchase, The high overall **drop-off rate** of **97.75%** suggests that the majority of users abandon the process at some stage before completing a purchase.
    * Half of the users who visit the homepage proceed to the product page, The other half drop off at this stage, which may indicate issues with the homepage's appeal, navigation, or load time.
    * A significant drop-off occurs at the **Product Page to Cart Page** stage, with **70%** of users who view a product page not adding any products to their cart, This suggests potential issues with product descriptions, images, pricing, or perhaps a lack of urgency or clear call-to-action.
    * The **Cart Page to Checkout Page** is similar to the previous stage, **70%** of users who add items to their cart do not proceed to the checkout, This could be due to unexpected costs (e.g., shipping), complicated checkout processes, or concerns about payment security.
    * Half of the users who start the checkout process complete the purchase, The remaining **50%** drop off, which might be due to last-minute doubts, a complex checkout process, or issues with payment methods.

## Recommendations
Here are our recommendations based on our findings:
  * **Homepage Optimization:**
    * Ensure the homepage is engaging and directs users effectively to product pages.
    * Highlight popular products, deals, and clear navigation paths.
  * **Product Page Enhancements:**
    * Improve product images, descriptions, and overall presentation.
    * Clearly display pricing and any available discounts.
    * Add persuasive elements like customer reviews and testimonials.
  * **Cart Page Improvements:**
    * Provide a clear and simple summary of the cart contents.
    * Ensure transparency in pricing, including shipping and taxes.
    * Offer incentives like free shipping or discounts to encourage checkout.
  * **Checkout Process Streamlining:**
    * Simplify the checkout process to minimize steps and reduce friction.
    * Provide multiple, secure payment options.
    * Offer reassurances like return policies, customer support, and security badges.

By addressing the identified issues, we can enhance user satisfaction and encourage more users to complete their purchases.
# Armut_Basket_Analysis

![Açıklama](https://theme.zdassets.com/theme_assets/401552/1fcb26e008e6503497bb522c9c84da950d1e8e31.png)

Armut is Turkey's largest online service platform that connects service providers with customers seeking various services. Users can conveniently access services such as cleaning, renovation, and moving through their computers or smartphones with just a few taps.

The main objective is to create a product recommendation system using Association Rule Learning based on a dataset containing information about users who have utilized services and the services and categories they have chosen.

## Dataset story

The dataset consists of the services that customers have received along with the categories of these services. Additionally, it includes the date and time information for each service received.

### Variables:
- UserId: Customer number, representing unique identifiers for each customer.
- ServiceId: Anonymized service identifiers that belong to different categories. For example, a service like "Sofa Cleaning" can fall under the "Cleaning" category. Each ServiceId can be found in different categories and may represent different services under different categories. For instance, a ServiceId with CategoryId 7 might represent "Radiator Cleaning," while the same ServiceId with CategoryId 2 might represent "Furniture Assembly."
- CategoryId: Anonymized category identifiers, representing different service categories such as Cleaning, Moving, Renovation, etc.
- CreateDate: The date when the service was purchased, providing the timestamp for each transaction.



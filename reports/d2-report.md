The Multiway graph
================
Anirudh Singh
March 22, 2019

Introduction
------------

Questions I was trying to answer: - What type of app should I make if I want to make money? - Where can I not be extravagant with pricing?

State the number of observations:

List the variables:

-   Price ($) - This is the price of the app one has to pay to purchase on the appstore
-   user\_rating (1,1.5,2,2.5,3,3.5.....5) - These are the total ratings the app has received over time for all versions (serves as a test to see if pricing it at that level was successful) - It has 10 levels
-   primary\_genre (Travel...) - This is the type of application on the app store based on the function it serves. - It has 23 unique genres

State the graph type: Multiway Plot

Explain why the graph type is suited to the data structure:

-   Want to look at popular application and their prices and how they vary in different genres.

-   Since we are trying to show how price varies in several categories of application based and we also want to show how user ratings affect the price. This is the ideal plot.

Explain each design choice and cite its supporting reference

-   Using only apps with price less than $42 - getting rid of outliers - better scaling. - applications costing are unpopular.

-   using cont\_rating as colour - helps establish relationship between cont rating and price. (if any)
-   etc

Observations: - Ratings come after the purchase (1-5) - 0 means not been rated. - Most applications are 0-10 dollars. - Medical apps have a higher range - Shopping apps tend to be free since having the customer pay for the app would drive them away - Same goes for news apps and social networking - 17+ are usually paid (might be wrong) - What type of app to produce if you want to make money -general rule of thumb - specificity

     -- Games and Music, maybe even productivity

<img src="../figures/0402-multiway-appStore.png" width="100%" />

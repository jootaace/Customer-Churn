# Customer Churn Project
This project involves the development of a classical machine learning model for a Telecommunication Company to predict customer churn, facilitating a data-driven retention program.

#### Classification Challenge:

In a Telco Company, the latest reviews have shown churn (number of customers leaving the company) asone of the major drivers of costs. The company would like to create a data driven retention program toreplace the current one. Therefore, they would like to contact some potential churners by means of an MLmodel before they leave (they currently contact the clients with the largest tenure). The company capacityis to contact a maximum of 200 clients per month.

On the other hand, getting the data (where “churners” are identified) takes one month (that means, it isnot until the end of May that we know which clients “churned” in April).

We have been given a dataset with the information of the active clients in a certain month and whetherthey left or not in subsequent months. Each row represents a customer; each column contains customer’sattributes.

The dataset includes information about:
- Customers who left within the month, next month or following two months – the columns arecalled “churn_<xx>_month” respectively, where xx is 1, 2, or 3
- Services that each customer has signed up for – phone, multiple lines, internet, online security,online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method,paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

The practice consists of developing an ML model (you can get inspiration from the example we saw inclass). That tries to solve for this problem.

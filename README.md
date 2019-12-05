# Customer-Segmentation
Customer Segmentation using  K-Means clustering and Gaussian mixture modeling.

In this project, we'll look at purchasing data for clients of a wholesale distributor and attempt to use purchasing behavior to identify a way to predict what group each client belongs to. The characteristics of the grouping is unknown, we simply want to see if we can put similar observations (in this case, clients) into the same group. We'll then compare these predicted groupings to the true channels (Hotel/Restaurant/Cafe and Retail) each client belongs to.

Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. Being equipped with this information can assist a company engineer future products and services that best satisfy the demands or needs of their customers.
Data

The customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the UCI Machine Learning Repository.

Features

    Fresh: annual spending (m.u.) on fresh products (Continuous);
    Milk: annual spending (m.u.) on milk products (Continuous);
    Grocery: annual spending (m.u.) on grocery products (Continuous);
    Frozen: annual spending (m.u.) on frozen products (Continuous);
    Detergents_Paper: annual spending (m.u.) on detergents and paper products (Continuous);
    Delicatessen: annual spending (m.u.) on and delicatessen products (Continuous);
    Channel: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
    Region: {Lisnon - 1, Oporto - 2, or Other - 3} (Nominal)

Note: (m.u.) is shorthand for monetary units.

For this project we'll attempt to predict which channel each client belongs to, so we won't look at this column until after we've segmented the data using clustering techniques.

This project requires Python 2.7.

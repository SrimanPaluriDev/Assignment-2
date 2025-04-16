escription

This project preprocesses a car dataset (train.csv) to prepare it for machine learning tasks. It includes handling missing values, extracting numeric values from attributes with units, and one-hot encoding categorical variables. The dataset contains 5,847 rows and 14 columns, including features like Mileage, Engine, Power, Fuel_Type, and Transmission.

Features





Loads and explores the car dataset using pandas



Imputes missing values with mode or median



Extracts numeric values from columns with units (e.g., Mileage, Engine, Power, New_Price)



Converts price units (Lakh, Cr) to a consistent numeric format



One-hot encodes categorical variables (Fuel_Type, Transmission

Tasks Performed





Missing Values: Imputes missing values in Engine, Power, Seats, and New_Price using mode or median. Rows with excessive missing values are dropped.



Unit Removal: Extracts numeric values from Mileage, Engine, Power, and converts New_Price (Lakh/Cr) to a consistent numeric format.



One-Hot Encoding: Encodes categorical variables Fuel_Type and Transmission using pandas' get_dummies.



# Experiment 14

## Data Binning and Data Formatting using Python

### Name: Bhomik V Keshi

### PRN: 25070123172

---

## Aim

To understand and perform data binning and basic data formatting operations using Python.

---

## Tools Used

* Python
* Pandas
* NumPy

---

## Description

In this experiment, we created datasets using Python and performed different operations like binning the data into categories, changing data types, formatting text, sorting values, and counting categories.

---

## Algorithm

1. First, we imported the required libraries like pandas and numpy.

2. Then we created a dataset of products which contains product name, price, and units sold.

3. After creating the dataset, we converted it into a DataFrame using pandas.

4. We performed data binning on the Price column by defining ranges (bins) and assigning labels like LOW, MEDIUM, and HIGH.

5. Similarly, we applied binning on Units_Sold to divide sales into categories.

6. Next, we checked the data types of all columns and converted Units_Sold from integer to float type.

7. After that, we formatted the Product column by converting all names into uppercase.

8. We also rounded the Price values (even though they were already integers).

9. Then we sorted the dataset based on Price in both ascending and descending order.

10. We displayed the unique values present in the Price_Category column.

11. After that, we created another dataset related to orders which includes order value, delivery time, and distance.

12. We applied data binning on Order_Value to classify it into LOW, MEDIUM, and HIGH order categories.

13. Finally, we counted how many values fall into each category using value_counts().

---

## Observation

* Data binning helps to group numerical values into categories which makes data easier to understand.
* Formatting like uppercase makes the data look more consistent.
* Sorting helps in analyzing smallest and largest values easily.
* There was a small mistake in binning of order value due to using the wrong bin variable, so all values came under LOW category.

---

## Conclusion

From this experiment, I learned how to organize and format data using pandas. Data binning is useful for classification, and other operations like sorting and type conversion are important for data analysis.

---

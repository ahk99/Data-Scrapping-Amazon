# Data-Scrapping-Amazon
Scrapping washing machine data from Amazon

[Amazon Washing machine](https://www.amazon.in/s?k=washing+machine)

In this repository I have mainly focussed on scrapping data from amazon ecommerce site and then cleaning the data.

# Data Collection

The data obtained is that of the washing machine details that includes:

    *Name of the product

    *Rating out of 5

    *Capacity

    *Access location

    *Brand

    *Price


Result: Obtained almost 400+ data. Collected data contains numerous null values.

# Data Cleaning

Since the data obtained is not in a standard format and  thus cannot be used in performing statistical calculations, also since the data contains null values, the dataframe needs to be cleaned and processed.

The cleaning task included:

    *Dropping all the  rows that contains atleast one NaN value.

    *Removing unnecessary substrings or repetative substrings which are not seen usefull for the statistical operations and analysis.

    *Renaming certain columns to provide a better meaningfull title for the column.


#Thank You.

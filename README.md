# Nashville-Housing-Data-Cleaning

# Source:
https://github.com/AlexTheAnalyst/PortfolioProjects/blob/main/Nashville%20Housing%20Data%20for%20Data%20Cleaning.xlsx

# Task:
The task of this project is to clean the Nashville Housing Data. 
The data contained duplicates, Nulls and Grouped values that needs to be in separate columns.

Steps taken to complete this task include the following:

1. Import the raw Excel data into MSSQL.

2. View and review the data.

3. STANDARDIZE THE SaleDate FORMAT (BEING DATETIME FORMAT, Converting to Date only format)

4. POPULATE PropertyAddress NULL DATA

5. BREAK OUT PropertyAddress INTO INDIVIDUAL COLUMNS (ADDRESS, CITY)

6. BREAK OUT OwnerAddress INTO INDIVIDUAL COLUMNS (ADDRESS, CITY, STATE) 

7. CHANGE Y AND N TO YES AND NO IN "SoldAsVacant" FIELD

8. REMOVE DUPLICATES 

9. DELETE UNUSED COLUMNS

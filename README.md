1. **To Replace the null values**
Using Go To Special
Select the column (or whole table).
Press Ctrl + G (or F5) → Click Special.
Choose Blanks → Click OK.
Now Apply filters to the column and unselect blanks then automatically blanks are removed.

2. **To Remove Duplicates**
Select the column (or whole table).
Go to Data > Delete Duplicates.

3. **Standardize text values like gender, country names and Rename column headers to be clean and uniform**
Select your table → Data > Get & Transform > From Table/Range.
In Power Query:
Use Transform > Format → change case (capitalize, lowercase, etc.).
Use Replace Values (e.g., replace "mALe" with "Male")

4. **Convert date formats to a consistent type and Check and fix data types**
Select the column or range with dates.
Go to Home > Number Group > More Number Formats (small arrow).
Select Number.
Choose a consistent format like 5000 OR 5000.oo.
Set datatypes like CustomerID, Name in Text
Click OK.

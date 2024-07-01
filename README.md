# Data Cleaning Project

## Project objective:

  This is a project that involves data cleaning of a NahviLLeHousing Dataset using SQL. The below summary highlights the tasks performed for data cleaning & data standardisation.

   **1.Standardize Date Format:**
   
   Converts the saledate column to a standardized date format.

**2.Populate Property Address Data:**

Populates missing PropertyAddress values by matching ParcelID from other records in the same table.

**3.Breaking Out Address into Individual Columns:**

Splits PropertyAddress into PropertySplitAddress (street address) and PropertySplitCity using string manipulation functions.

**4.Breaking Out Owner Address into Individual Columns:**

Splits OwnerAddress into OwnerSplitAddress (street address), OwnerSplitCity, and OwnerSplitState using PARSENAME and string manipulation functions.

**5.Change 'Y' and 'N' to 'Yes' and 'No' in 'SoldAsVacant' Field:**

Converts values in the SoldAsVacant field from 'Y' to 'Yes' and from 'N' to 'No'.

**6.Remove Duplicates:**

Uses ROW_NUMBER() to identify and filter duplicate records based on specific columns (ParcelID, PropertyAddress, etc.).

**7.Delete Unused Columns:**

Drops columns OwnerAddress, TaxDistrict, PropertyAddress, and SaleD from the table to remove redundant or unnecessary data.

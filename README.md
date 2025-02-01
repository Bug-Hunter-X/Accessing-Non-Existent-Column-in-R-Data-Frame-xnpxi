# Accessing Non-Existent Column in R Data Frame
This repository demonstrates a common error in R programming: attempting to access a column in a data frame that does not exist. The `bug.R` file contains the erroneous code, while `bugSolution.R` shows the corrected version.

The error occurs because the code tries to access column 'C' in the `data` frame, but this column is not defined.  This leads to an error message indicating that the object 'C' is not found.

The solution involves carefully checking column names and potentially using safer methods (e.g., `dplyr::select`) to access columns, which handles missing columns more gracefully.
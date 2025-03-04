## Overview 
This is the Income and Expense report of a real estate firm in NY. Raw bank statements of the firm were imported, processed and summarized into a user-friendly, interactive Excel file. [Link to the file](https://github.com/ashergeo/My-Portfolio/raw/main/assets/Microsoft%20Excel/Abraham%20Properties%202023.xlsx)
<br>
#### Following are the list of sheets included within the file along with a short description:
### Data Processing

- **Description:** Initial data import and transformation using Excel's Power Query Editor.
- **Techniques Used:** Get Data from Text/CSV, data cleaning with functions like IF, LEFT, RIGHT, MID, SEARCH, ISBLANK, DATE, COUNTIFS.

### Checking Account Sheet

- **Description:** Detailed accounting of monthly transactions with a summary table for quick insights.
- **Tables:** 
  - Monthly summary table (image format).
  - Detailed transaction table with columns for Date, Type, Description, Debit (-), Credit (+), and Balance.
- **Interactive Features:** Slicer for filtering by month.

### Individual Totals

- **Description:** Sheet to provide individual totals based on unique entries in the Description column from the Checking Account sheet. It also includes a table that shows the Individual Totals summary. 
- **Data Validation:** Dropdown list of unique entries. Conditional Formatting added to highlight in the Individual Totals table the selected entry. 
- **Formula Used:** `=FILTER(Table_CheckAcct,Table_CheckAcct[Individual Index]=$D$2)`.

### Check Register

- **Description:** Table with details of issued checks.
- **Columns:** Number, Date, Description, Amount.
- **Interactive Features:** Slicer for filtering by payee (e.g., 'MCK Engineering', 'RC Commissioner of Finance', 'US Tax Service').

## Screenshots
**Checking Account:**  
    ![Checking Account](https://github.com/ashergeo/My-Portfolio/blob/main/assets/Microsoft%20Excel/Checking%20Account.png)   
    

**Individual Accounts:**  
    ![Individual Accounts](https://github.com/ashergeo/My-Portfolio/blob/main/assets/Microsoft%20Excel/Individual%20Accounts.png)   
    

**Check Register**   
    ![Check Register](https://github.com/ashergeo/My-Portfolio/blob/main/assets/Microsoft%20Excel/Check%20Register.png)


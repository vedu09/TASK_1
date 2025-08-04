# TASK_1 : DATA CLEANING & PREPROCESSING

### DATASET : [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) 

#### SCREENSHOTS :<br>

**RAW DATA :** <br>
<img src="https://github.com/vedu09/TASK_1/blob/main/screenshots/Screenshot%202025-08-04%20221719.png" alt="Netflix Dashboard" width="800"/>

<br>

**CLEANED DATA :**<br>
<img src="https://github.com/vedu09/TASK_1/blob/main/screenshots/Screenshot%202025-08-04%20221042.png" alt="Netflix Dashboard" width="800"/>


<br>
<br>

**Step 1: Standardized Column Names :**<br>
  Changed all column headers to UPPERCASE for consistency.

**Step 2: Updated Data Types :**<br>
  + Converted DATE_ADDED column to Date format.
  + Converted RELEASE_YEAR to Integer type.

**Step 3: Checked for Duplicates :**<br>
No duplicate records were found, so no rows were removed.

**Step 4: Removed Missing Titles :**<br>
Deleted rows where the TITLE column was empty.

**Step 5: Filled Missing Cast Data :**<br>
Replaced null values in the CAST column with "NOT PROVIDED".

**Step 6: Removed Invalid Records :**<br>
Removed rows that didn’t represent real Movies or TV Shows.

**Step 7: Handled Missing Country Information :**<br>
Replaced null values in the COUNTRY column with "Unknown".

**Step 8: Extracted Release Month :**<br>
Added a new column RELEASE_MONTH by extracting the month from the DATE_ADDED column.

**Step 9: Fixed Rating Column Issues :**<br>
Moved values that were mistakenly entered in the DURATION column back to the correct RATING column.

**Step 10: Labeled Missing Durations :**<br>
Replaced null values in the DURATION column with "Missing Duration".

**Step 11: Final Formatting :**<br>
  + Applied Table Design for better readability
  + Froze the header row for easy scrolling
  + Adjusted column spacing
  + Enabled Wrap Text to fully display cell content

# Retail Sales Dataset Analysis
## Overview

This project demonstrates a series of Excel techniques applied to organise, analyse, and extract insights from a dataset. The focus is on efficient data manipulation using tables, formulas, and conditional functions.

## Key Features & Tasks

1. Convert Data Range into a Table
All data from columns A to H was converted into an Excel Table to enable easier sorting, filtering, and formula application.
(Insert screenshot of table here)

2. Filter and Sort Data by Age
Applied Excel’s Filter function on the Age column and sorted values from largest to smallest to identify trends and patterns by age.

<img width="493" height="194" alt="Screenshot 2025-12-08 at 16 16 51" src="https://github.com/user-attachments/assets/21aaece3-aa91-4913-9142-0dab970e9a51" />

3. Calculate Total Commission
Used the SUM function to calculate the total commission across all entries.

Cell: P10
Formula:
=SUM(H2:H100)

<img width="490" height="127" alt="Screenshot 2025-12-08 at 16 18 00" src="https://github.com/user-attachments/assets/26b933f2-80db-4f93-92fc-bb60c36b3c06" />

4. Calculate Average Commission
Used the AVERAGE function to determine the mean commission value.

Cell: P11
Formula:
=AVERAGE(H2:H100)

<img width="493" height="188" alt="Screenshot 2025-12-08 at 16 19 23" src="https://github.com/user-attachments/assets/63205db3-33b2-4520-a3a6-1a46d25a11ee" />

5. Retrieve Specific Data with VLOOKUP
Used VLOOKUP to find the commission for a specific customer ID.

Formula:
=VLOOKUP(J2, A:H, 8, FALSE)

<img width="986" height="391" alt="Screenshot 2025-12-09 at 14 42 31" src="https://github.com/user-attachments/assets/590f8a6a-c58b-40b2-8a83-5eac997743fa" />

6. Extract Unique Values
Used the UNIQUE function to list distinct entries from a column (e.g., customer names or regions).

Formula:
=UNIQUE(Table1[Product Category])

<img width="1100" height="284" alt="Screenshot 2025-12-09 at 15 04 20" src="https://github.com/user-attachments/assets/98f8f7cd-c4bb-4239-8aa1-7649e2639d26" />

7. Conditional Summing
Used SUMIFS to sum values based on specific criteria, e.g., total commission by region or age group.

Formula Example:
=SUMIFS(H2:H100, B2:B100, "Region1")

<img width="1064" height="147" alt="Screenshot 2025-12-09 at 15 07 53" src="https://github.com/user-attachments/assets/c748e2d6-6817-42ab-9bcd-0c1a039145d7" />

8. Conditional Averaging
Used AVERAGEIFS to calculate averages for subsets of data.

Formula Example:
=AVERAGEIFS(H2:H100, B2:B100, "Region1")

<img width="1013" height="147" alt="Screenshot 2025-12-09 at 15 06 56" src="https://github.com/user-attachments/assets/02ed9f63-7202-4392-bb71-d3c1aeb931ee" />

9. Transpose Unique Values
Combined TRANSPOSE and UNIQUE to display unique values horizontally rather than vertically.

Formula:
=TRANSPOSE(UNIQUE(Table1[Gender]))

<img width="1069" height="221" alt="Screenshot 2025-12-09 at 15 12 04" src="https://github.com/user-attachments/assets/1e3f63d0-9b06-413d-be73-1a7da3e35ba7" />

10. Count Total Orders
Used the COUNTIF function to count the number of orders by evaluating all Transaction IDs greater than zero.

Formula:
=COUNTIF(Table1[Transaction ID], ">0")

<img width="864" height="195" alt="Screenshot 2025-12-09 at 15 24 39" src="https://github.com/user-attachments/assets/f33790d5-550b-4f0f-a70a-1a5c118e4d95" />


By applying these Excel techniques, I am able to organise and analyse data more efficiently, identify patterns and trends, and extract meaningful insights quickly. Skills such as creating tables, using formulas like SUM, AVERAGE, VLOOKUP, SUMIFS, AVERAGEIFS, and COUNTIF, as well as working with UNIQUE and TRANSPOSE, enable me to manipulate datasets effectively, perform conditional calculations, and generate clear, accurate reports. Mastering these functions enhances my ability to work confidently in Excel and supports faster, more informed data-driven decision-making.

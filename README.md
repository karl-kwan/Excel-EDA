## Exploratory Data Analysis on Excel

This is an exercise from https://www.youtube.com/watch?v=_g5roKHj95o&ab_channel=KenjiExplains

The excel workbook contains 2 worksheet: before and after.

Procedures of performing EDA:

<img width="625" alt="image" src="https://github.com/user-attachments/assets/c300b280-db88-496c-89ad-4e95b30b6d69">

1. Change it into table form - Control + T
2. [Manager]: Odd spacing → trim() to clean the spacing
3. [Quantity]: strange float for quantity → round up to integer (=roundup([@quantity], 0))
4. Added [Country]
5. Removed duplicates: 5 rows
6. Used Add-ins feature to add Analysis ToolPak and used its Descriptive Statistics function to better understand the data.

<img width="321" alt="image" src="https://github.com/user-attachments/assets/6a4d5419-e844-4fe2-b359-981c6146c81f">

<img width="460" alt="image" src="https://github.com/user-attachments/assets/07b5c964-dea6-4e3d-abef-81edc738c1ec">


7. Used box plot to find out any outliers.
    
<img width="772" alt="image" src="https://github.com/user-attachments/assets/23697087-8698-4c71-89ba-a730fb49ef90">
    
8. Added a column: [Revenue]
9. Created pivot table to summarize cols to answer the question
10. Created a dashboard for knowing manager's performance by using xloopup, sumifs and data validation to create list dropdown menu.

Final version:
<img width="1306" alt="image" src="https://github.com/user-attachments/assets/3e6ebfc0-44c9-4c8b-a4b7-bf5f3c2ab7de">

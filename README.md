## Exploratory Data Analysis on Excel

This is an exercise from https://www.youtube.com/watch?v=_g5roKHj95o&ab_channel=KenjiExplains

The excel workbook contains 2 worksheet: before and after.

Procedures of performing EDA:

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3845f8e4-7b31-47c2-8890-71d7599e3c90/2220ca1f-0b2f-4886-be9f-39284de8871f/image.png)

1. Change it into table form - Control + T
2. [Manager]: Odd spacing → trim() to clean the spacing
3. [Quantity]: strange float for quantity → round up to integer (=roundup([@quantity], 0))
4. Added [Country]
5. Removed duplicates: 5 rows
6. Used Add-ins feature to add Analysis ToolPak and used its Descriptive Statistics function to better understand the data.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3845f8e4-7b31-47c2-8890-71d7599e3c90/4448feef-0222-4451-b3fc-58ea4917b12f/9b3c84f3-5628-4731-b3c2-5557fd6ddd9d.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3845f8e4-7b31-47c2-8890-71d7599e3c90/de2a2bb0-a924-4fb1-9484-95c6eddd8e80/image.png)

7. Used box plot to find out any outliers.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3845f8e4-7b31-47c2-8890-71d7599e3c90/07f4ae30-59f3-49cb-8a74-20b2c8d82d32/image.png)
    
8. Added a column: [Revenue]
9. Created pivot table to summarize cols to answer the question
10. Created a dashboard for knowing manager's performance.

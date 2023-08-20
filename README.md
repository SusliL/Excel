# Excel
/*Data Cleaning with Excel*/

/*Checking Spelling*/
1. Selected Column L (Credit Card_Type)
2. Clicked Review
3. Selected Spell Check 

/*Remove Empty Rows*/
1. Clicked Filter from the Data tab
2. Clicked filter arrow in the (Cust_Name) Column
3. Deselected (Select All) And only selected (Blanks)
4. Ensure blanks were not necessary to the data and deleted.

/*Removed Ducplicate Rows*/
1. Selected unique column (Order_id)
2. Selected Conditional Formatting > Highlight Cells Rules > Duplicate Values
3. Reviewed highlighted portions to ensure they were duplicates and deleted.

/*Using PROPER FUNCTION to fix Inconsistencies in Data*/
1. Selected cell A2 and insrted Row
2. in new A2 cell typed =PROPER(A1)
3. Hovered over the bottom-right corner of cell A2 and dragged FILL HANDLE accrose to last column

/*Changing Date formatting*/
1. Selected Column Z (Order_Ship_Date)
2. Selected More NUMBER FORMATS from Home Tab
3. Selected DATE from category list
4. In FORMAT cells under Locale , selected ENGLISH(US)
5. Under TYPE selected preferred data structure

/*Splitting (Customer_Name) to (First_Name) and (Last_Name)*/
1. Selected Column A (Cust_Name) and INSERTED 2 columns
2. In cell A1, typed (Customer_Firstname)
3. In cell B1, typed (Customer_Lastname)
4. In cell A1, typed =LEFT(C2,SEARCH(" ",C2,1))
5. In cel B2, typed =RIGHT(C2,LEN(C2)-SEARCH(" ",C2,1))
6. Double cliked FILL HANDLE for both cells A2 and B2

#Excel 
/*Useful Functions for Analysis*/

/*Using IF to apply one condition*/
1. Selected column AF, and clicked INSERT
2. Titled column AF2 (Complete)
3. In cell AF2, typed =IF(AE2 = "Complete" , "Yes","No")
4. Double Clicked FILL HANDLE

/*Using COUNTIF to count the number of cells that meet a specified criterion*/
1. Selected cell BX2 and typed (Count Visa Card)
2. Select BY2 and typed =COUNTIF(N2:N195,"Visa")
3. Result: Number of Visa Credit Card Types

/*Using VLOOKUP to look up date in a table organized vertically*/
1.In cell K2,L2,M2, typed VLOOKUP, Startup Name, Amount in USD
2.Selected and copied cells from C9:C15 and pasted in cell L3.
3.In cell M3, typed =VLOOKUP(L3, C2:I113, 7, FALSE) 
4.FILL HANDLED from M2 down to M9 
5.Result: Gave me Amount in USD for all Selected Start Up Names 










Create an application for VB Landscape Supplies.  This application will allow a person to order Mulch.  
Ensure all input is validated per the requirements
Program should be broken into procedures and functions as taught in Programming 1.
 
Input
Name (required)
Zip Code (required for any order and can only be 41042, 41022, 41091 if delivery option is Delivery)
Mulch Type (required and must be one of the following):
•	Black Shredded - $7.90
•	Black Chips - $7.00
•	Brown Shredded - $7.90
•	Brown Chips - $7.00
•	Red Shredded - $7.90
•	Red Chips - $7.00

Number of Bags (required, >0, < 51)
Delivery Option (either Pick Up or Delivery) 
Note:  only deliveries to 41042, 41022, and 41091 zip codes.  If delivery is chosen and other zip code is entered, show error message.

Process
1.	Customer will complete form. 
2.	Customer can add multiple types of mulch to order by click “ADD” 
3.	After clicking “ADD”, mulch type, number of bags and total should be displayed on Listbox
4.	After clicking “ADD”, mulch type, number of bags should be cleared for next item. 
5.	If additional type and bags are entered, repeat beginning at 2
6.	Once all products have been entered, user clicks “Total” 
7.	A total line should appear on the list box showing: 
o	Total for all bags
o	Tax (7%)
o	Delivery (if chosen and based on zip code) 
	41042 - $10.00
	41022 - $12.00
	41091 - $15.00
o	Grand Total


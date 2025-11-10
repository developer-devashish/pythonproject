# pythonproject

🧾 BFF Café Billing System (Tkinter + Excel + Receipt Popup)
This project is a billing system for a café, developed using Python Tkinter.
It allows the user to enter item quantities, calculates the bill, shows receipt in a popup window, and saves the bill history automatically inside an Excel file.

✅ Features
Feature	Description
GUI Application	Built using Tkinter (Python)
Auto Bill Number	Random 4-digit bill number generated for each transaction
Timestamp	Captures current date & time of billing
Excel Data Save	Automatically stores bill data into Cafe_Bill_Record.xlsx
Receipt Popup	Opens a separate window showing formatted bill/receipt
Reset Functionality	Clears input values and generated bill details
Real-Time Calculation	Automatically calculates total, tax (5%), grand total

🛠 Libraries Used
Library	  |  Purpose
-------------------------------------
Tkinter	  |  GUI (user interface)
openpyxl	| Save bill records into Excel
random	  |  Generate bill number
time	    |  Fetch date & time
os	      |  Check & create Excel file

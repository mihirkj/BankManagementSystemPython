# BankManagementSystemPython
A bank management system written in Python 3 with GUI made using Tkinter and the database using SQLite.

This program when started shows the users an initial screen having two options for either to Register (to be able to use the banking services) or to Login if already registered.

Registration Window:
	The registration window prompts the user to enter their name, desired PIN and initial deposit amount in rupees. Care is taken in the program to handle invalid entries like if the user leaves entry fields blank or enters alphabetical characters in places meant for numeric characters. Also the PIN is masked with ‘*’ symbols for security purposes. If all the inputs are valid then the user is registered and a dialog box tells the user their account number which they should note down.

Login Window:
	This window asks the user for their name, account number and PIN. The PIN is masked and if the user enters invalid information all the entry field are cleared and they are notified for the same. If all goes well then they are taken to the services screen.

Services Screen:
	After login the user is greeted on the title bar of the services screen. There are three kinds of services available to the users:
  <ul>
    <li> Deposit: to deposit the specified amount into their account. </li>
    <li> Withdraw: to withdraw the specified amount from their account. If the user does not have sufficient balance to withdraw they are notified for the same in a dialog
        box. </li>
    <li> Check balance: to check the current available balance of the account. </li>
   </ul>
   
  

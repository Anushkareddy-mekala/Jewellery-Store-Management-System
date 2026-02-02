# Jewellery-Store-Management-System
Jewellery Store Management System is a Java console application that manages gold and silver jewellery items, customer details, bill generation with GST and discounts, payment processing, and cash note management. It uses OOP concepts like inheritance, encapsulation, and real-time billing features. 

__Features__
•	Customer information management
•	Gold and Silver jewellery selection
•	Automatic price calculation based on weight
•	3% GST calculation
•	10% Discount for bills above ₹100000
•	Bill generation
•	Cash payment handling
•	Change return using different currency denominations
•	Console-based interactive menu

__Technologies Used__
•	Java
•	OOP Concepts
•	Scanner Class for Input
•	Console Application

__OOP Concepts Implemented__
•	Encapsulation – Private variables with getter methods
•	Inheritance – GoldItem and SilverItem inherit from JewelleryItem
•	Polymorphism – Method overriding behavior via parent reference
•	Abstraction (Basic Level) – Logical separation of billing and cash handling

__Class Description__
1. JewelleryItem
•	Parent class
•	Stores item ID, name, type, weight, and price per gram
•	Calculates total price
2. GoldItem
•	Inherits JewelleryItem
•	Default price: ₹10000 per gram
3. SilverItem
•	Inherits JewelleryItem
•	Default price: ₹1000 per gram
4. Customer
•	Stores customer ID, name, and phone number
5. Bill
•	Generates bill
•	Adds GST (3%)
•	Applies 10% discount if total > ₹100000
•	Displays final amount
6. CashManager
•	Manages available currency notes
•	Deducts notes while returning change
•	Displays remaining notes
7. Main
•	Entry point of the application
•	Handles user input and overall flow

__How It Works__
1.	User enters customer details
2.	User selects jewellery type
3.	User enters item details and weight
4.	System calculates price + GST
5.	Discount applied if eligible
6.	Bill displayed
7.	Customer pays amount
8.	System calculates change
9.	CashManager returns notes

__Sample Flow__
Enter Customer ID
Enter Customer Name
Enter Phone Number
Select Jewellery Type
Enter Item Details
Bill Generated
Enter Paid Amount
Change Returned

__Advantages__
•	Easy to use
•	Demonstrates strong OOP basics
•	Useful for beginner Java learners
•	Real-world application example

__Future Enhancements__
•	GUI Interface
•	Database Integration
•	Multiple Items in One Bill
•	Admin Login System
•	Digital Payment Support

__Output__

=== Jewellery Store Management System ===

Enter Customer ID: 1

Enter Customer Name: Anu

Enter Phone Number: 8765432109


Select Jewellery Type

1. Gold
2. Silver
1
Enter Item ID: 3

Enter Item Name: Chain

Enter Weight (grams): 7

Enter Price per gram: 10000

----- BILL -----

Customer Name : Anu

Item Name     : Chain

Base Price    :  ₹ 70000.0

GST (3%)      :  ₹ 2100.0

Final Amount  : ₹ 72100.0

Enter amount paid by customer: 75000

✅ Payment successful

Change to return: ₹ 2900.0

--- Remaining Notes ---

₹2000 : 9

₹500  : 19

₹200  : 28

₹100  : 10

₹50   : 10

₹20   : 200

₹10   : 200

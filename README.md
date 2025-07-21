🍔 iHungry Burger Shop Management System

This is a Java-based Command Line Interface (CLI) application developed as part of the iCD117 coursework at the **Institute of Computer Engineering Technology (iCET)**. The system manages customer orders, maintains records, and provides various features to ensure smooth operation for the iHungry Burger Shop.

📌 Features

1. **Place Order**
   - Auto-generates Order IDs ('B0001', 'B0002', ...).
   - Validates Customer ID (must be a 10-digit phone number starting with '0').
   - Stores Customer Name (if new).
   - Allows entry of Burger Quantity (must be > 0).
   - Automatically sets order status to 'PREPARING'.
   - Calculates total bill (each burger is Rs. 500).
   - Allows confirmation before finalizing the order.

2. **Search Best Customer**
   - Displays customers sorted by total purchases in descending order.

3. **Search Order**
   - Lets users search for orders by Order ID.
   - Displays full order details if found.

4. **Search Customer**
   - Lets users search by Customer ID.
   - Displays all orders placed by that customer.

5. **View Orders**
   - View all orders categorized by their status:
     - 'DELIVERED'
     - 'PREPARING'
     - 'CANCELLED'

6. **Update Order**
   - Allows updating **quantity** or **status** of orders that are still in 'PREPARING' state.

7. **Exit System**
   - Safely exits the program with a confirmation message.

 🛠️ Technologies Used

- Java (JDK 8 or higher)
- Command Line Interface (CLI)
- 'Scanner' for user input

## 🧾 Constants Used

'''java
public static final int PREPARING = 0;
public static final int DELIVERED = 1;
public static final int CANCEL = 2;
final static double BURGERPRICE = 500;

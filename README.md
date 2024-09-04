# Bakery Management System

The Bakery Management System is a console-based application that allows users to place orders from a bakery through a user-friendly interface. The system offers a login and registration portal, item search by subsequences, and a simple ordering and billing system. The goal is to provide a seamless ordering experience for bakery customers.

## Features

- **Registration and Login:**
  - The system starts with a registration and login portal.
  - Users need to enter their username and password (case-sensitive).
  - Login credentials are required for accessing the ordering system.

- **Item Search:**
  - Users can search for bakery items by entering any subsequence of characters.
  - The program will display all items that contain the entered subsequence, along with the item price and a unique serial number.
  - Example: If the user types `BuTrCks`, the system will display **BUTTER COOKIES**.

- **Order Placement:**
  - Users select items by entering the serial number and specifying the desired quantity.
  - If the user enters an incorrect serial number or a quantity exceeding available stock, the system prompts for re-entry.
  - After each selection, the user can decide whether to order more items or proceed to checkout.

- **Order Summary and Billing:**
  - Once the user completes their order, the program displays all the ordered items, quantities, and total price.
  - The system asks for delivery details, including name, address, postal code (PIN), and phone number.
  - A detailed bill is generated, which includes the user’s contact and delivery information along with their order.

- **Feedback Collection:**
  - After completing the order, the program collects feedback from the user.
  - Users are asked to rate the bakery from 1 to 5.
  - If the rating is 2 or below, the system asks for suggestions to improve the service.

## How It Works

1. **User Registration/Login**:
   - The user enters credentials (username and password) to either log in or register.
   - After successful login, the user proceeds to the next step.

2. **Search for Items**:
   - The user inputs a subsequence (e.g., "BuTrCks") to search for relevant items.
   - The system displays matching bakery items with serial numbers and prices.

3. **Order Selection**:
   - The user selects the serial number of the item they wish to order and inputs the quantity.
   - If the entered quantity exceeds stock, the system displays the available quantity.
   - The user decides whether to continue ordering or proceed to checkout.

4. **Order Summary and Bill**:
   - The user reviews their order's items, quantities, and total price.
   - The system prompts the user to provide delivery information.
   - A detailed order bill is generated and displayed.

5. **Feedback**:
   - The user provides feedback and rates the bakery’s service.
   - If the user rates 2 or below, they are prompted to share suggestions for improvement.

## Example Workflow

1. **Login/Registration:**
   - Enter username and password.
   - Successful login will take the user to the ordering menu.

2. **Item Search:**
   - Input a subsequence (e.g., `Co`) to display items such as **COOKIES** and **COFFEE**.

3. **Select Item and Quantity:**
   - Choose a serial number, and enter the quantity.
   - The system verifies stock and prompts accordingly.

4. **Checkout and Billing:**
   - The user confirms their order and provides delivery details.
   - The system displays a detailed bill.

5. **Feedback:**
   - Could you provide a rating and suggestions for improvement (if applicable)?

## Usage Instructions

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Abhi21sar/Bakery_Management_System.git

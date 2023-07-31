# Online Coffee Shop Application

This is an online coffee shop application developed for a local coffee shop. The application allows customers to create an account, view the menu, add items to their cart, and place orders. Additionally, coffee shop managers have special functionalities to manage the menu, update item quantities, and view customer orders.

## Features

### 1. Sign up/Sign in system for users

- Users can create an account with a unique username and password.
- Existing users can log in using their credentials.

### 2. View the menu

- Users can see the available coffee and food items on the main page.
- The menu includes categories such as espresso, cappuccino, pastries, sandwiches, etc.
- Users can view the inventory for each specific category.

### 3. Add to cart

- Users can add coffee and food items to their cart.
- The total price of the items in the cart is updated automatically.

### 4. Place an order

- When users click the "Place Order" button, the total price is displayed, creating an order.
- The system updates the inventory quantities accordingly.
- The coffee shop manager is notified of the new order.

### 5. Manager functionality

- The manager has special privileges to access additional functionalities.
- The manager can add new items to the menu.
- The manager can update item quantities in the inventory.
- The manager can view customer orders.

## Technology Stack

The application is built using Django, a powerful web framework for Python. Django offers many features and tools to create robust and scalable web applications.

## Setup Instructions

1. Clone the repository: `git clone https://github.com/ToxicMe/CoffeeShop`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run database migrations: `python manage.py migrate`
4. Create a superuser for manager access: `python manage.py createsuperuser`
5. Start the development server: `python manage.py runserver`
6. Access the application in your web browser at `http://localhost:8000`

## Additional Features

Feel free to extend the project and implement additional features based on your knowledge and skills. Some potential enhancements could include:

- Applying discounts or promotions to orders
- Integration with payment gateways for real transactions
- Email notifications to customers and managers
- Generating reports and analytics for the coffee shop's performance

Please remember to test your code thoroughly and make sure the user data and sensitive information is safe.

Enjoy using the Online Coffee Shop Application!

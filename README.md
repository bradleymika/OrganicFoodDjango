# OrganicFoodDjango
Group Project - Ordering Healthy Food




SYSTEM REPRESENTATION
Front-End (User Interface): User Authentication:
● Text fields for login (username/email and password) and registration.
● Login and register buttons for authentication. Navigation Menu:
● Options like Home, Restaurants, My Orders, and Logout.
● These options should be easily accessible and visible. Home Page:
● Displays options for browsing restaurants and placing orders.
● Categories like All, Vegan, Gym Friendly, etc., for filtering restaurants.
● Order Now buttons for selecting dishes and placing orders.
Restaurant Listings:
● Details such as cuisine type, ratings, and delivery areas.
● Categorized based on dietary preferences for easy browsing. Ordering Process:
● Redirects to a restaurant page upon clicking Order in a specific restaurant.
● Add to Cart buttons for adding dishes to the order.
 
 ● Checkout button for finalizing the order. Payment Options:
● Radio buttons for selecting payment methods like Cash on Delivery and Card.
● Secure payment processing for online transactions. User Account Management:
● My Orders page for viewing order history.
● Delete Order button for removing orders from the order history. Admin Features:
● Management interface for adding/editing restaurants and menus.
● Access to order details and user data for analytics and management purposes. Search and Filtering Options:
● Search bar for finding specific restaurants or dishes.
● Filters based on dietary preferences (vegan, gluten-free, etc.) for refining search results. User-Friendly Interface:
● Intuitive menu hierarchies and navigation for easy exploration.
● Clear and visually appealing design for a pleasant user experience.

 Back-End : Data Storage:
● The system will utilize MySQL for data storage. Data normalization techniques will be applied to ensure efficient storage and minimize redundancy. Indexes will be created on frequently queried fields to enhance performance.
Data Entry Mechanisms:
● Users will input data into the system through the frontend interface, which will include forms and input fields for adding new restaurants, menu items, user accounts, and processing orders. Validation rules and error handling mechanisms will be implemented to ensure data integrity and consistency.
Database Structure:
The database for the system will consist of several tables to store different types of data, including restaurants, menu items, users, and orders. Here's an overview of the database structure:

○ Data: Lists user's past orders, including restaurant name, date, order details, and total amount.
○ Users can view their order history to track spending and reorder favorite meals. Report 2: Restaurant Performance Report (Accessible by Restaurants & Admin)
○ Data: Analyzes order trends, revenue generated, and customer feedback (reviews) for a specific restaurant or time period.
○ This report helps restaurants understand customer preferences, optimize menus, and track sales performance.

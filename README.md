Vanier College 
Computer Science Department 
Final Report of 
Bubble Teahouse Management System

Project Scope:
Users:
Teahouse owners and employees are the primary end-users of the teahouse 
management system. Teahouse customers we will serve with our project.
• Teahouse owners will use the system to manage the employee information
and products, track the inventory and monitor sales data. The system will 
help the owner to manage the daily operations of the teahouse.
• Teahouse employees will use the system to process orders.
• Customers will use the system to browse the menu and place orders.
Potential clients: 
Ming Tao Xuan (Tea House),
Cha Do Raku (Salon de Thé), 
Salon de Thé CHAÏ Tea Lounge,
Cardinal Tearoom, and
Maison de thé Cha Noir - Thé & Tisanes
Project Functionalities:
Before midterm project evaluation:
1. Menu Display
The "Menu Display" functionality serves as the digital storefront for customers.
• This feature showcases the list of available bubble tea products, complete 
with high-quality images. 
• There are two main tea options we will offer: Iced Tea and Creamy Milk Tea.
• Clicking on the tea name will take customers to the order details.
2. Process Order:
The "Shopping Cart" functionality displays a summary of the items added to the 
cart during the order process.
• The primary feature enables customers to browse and make informed 
choices about their bubble tea selections.
• Customers can view the details of each item in the cart, including the type of 
tea, flavor, sweetness, ice choice, and quantity.
• It also displays the name and image of the tea.
• Another functionality ensures that the shopping cart accurately reflects the 
customer's order and its total cost.
• Clicking the “Add to Order” button will add all order details to the order list
and display a success message.
• Clicking the “Go to Cart” button will allow you to view the order list and 
proceed with the order.
• If a customer would like to order another tea, they could close the current 
window and go back to the main menu to add more teas. 
3. Shopping Cart:
The "Shopping Cart" functionality displays a summary of the items added to the 
cart during the order process.
• Customers can view the details of each item in the cart, including the type of 
tea, flavor, sweetness, ice choice, and quantity.
• The functionality ensures that the shopping cart accurately reflects the 
customer's order and its total cost.
• Clicking the “Check Out” button returns a message with total amount of this 
order and automatically completes the order by closing the order list 
window. 
4. Employee and Admin Log-In Window
• The log-in button is hidden in the right corner of the window. 
• Employees and admins can log in to their accounts with multiple 
choices by clicking on buttons. 
After Midterm Project Evaluation
5. Employee Management:
The "Employee Management" functionality provides administrators with the tools 
to effectively manage employee details within the Bubble Teahouse Management 
System.
• The feature enables administrators to add new employee records, providing 
a streamlined process for entering essential employee information such as 
name, ID number, contact details, email, and password.
• It also empowers administrators to modify existing employee records, 
allowing for the updating of critical information.
• Administrators can remove employee records when needed.
• This functionality maintains a comprehensive list of all employees, giving 
administrators an overview of each employee’s profile.
• Administrators can also conduct targeted searches based on specific 
employee identification criteria, such as name or employee ID.
• Selecting the Employee Management System option can direct the admin 
user to the Employee Management System page.

6. Product Management:
The "Product Management" functionality equips administrators with the necessary 
tools to effectively oversee and control the product information.
• This feature allows administrators to seamlessly add new product records, 
streamlining the process of inputting crucial product information, including 
product ID, name, ingredients, and price.
• Furthermore, it empowers administrators to effortlessly modify existing 
product records, ensuring that the product details are kept up to date and 
accurate.
• In cases where products need to be removed from the menu, administrators 
can efficiently delete product records.
• The product management functionality offers a comprehensive view of all 
products available within the teahouse, providing administrators with an 
overview of each product's profile.
• Administrators can also execute targeted searches based on specific product 
identification criteria, such as product name or product ID, simplifying the 
retrieval of product information within the system.
7. Inventory Management:
The "Inventory Management" functionality equips administrators with the 
essential tools to effectively control material inventory.
• This feature streamlines the process of handling inventory items, enabling 
administrators to efficiently add new inventory records. It facilitates the 
entry of critical inventory information, encompassing inventory ID, name, 
type, unit of measurement, and other relevant details.
• Administrators can also smoothly modify existing inventory records, 
ensuring inventory details are kept accurate and up to date.
• When circumstances require the removal of inventory items from stock, 
administrators can effortlessly delete inventory records.
• This functionality offers a consolidated view of all inventory items available 
within the teahouse, providing administrators with an overview of each 
item's profile and its specific attributes.
• Administrators can also perform targeted searches based on specific 
inventory identification criteria, such as inventory name or inventory ID. This 
streamlines the retrieval of inventory information, contributing to effective 
inventory control within the system.
8. Employee Information 
The employee information window allows employees to view their basic 
information after logging in with their employee ID and password.
• Employees can read details like their employee ID, name, email 
address, phone number and department.
Bubble Tea Rest API
We have designed a page for Employe Management for communication with REST 
API for our database. 
• Administrators can easily search, add, update, delete using employee 
ID, and view all employee information through our REST API and WPF 
user interface.
• Our local host address is https://localhost:7254/swagger/index.html
• We have included the results of trying out our REST API in the PDF 
called Swagger_BubbleTeaRESTAPI.pdf.
Bubble Tea Unit Test
Unit test for user authentication
When testing login functionality in unit tests, we would like to focus on the logic 
that ensures a user can successfully authenticate. Here are some key aspects that 
we considered:
1. Valid Credentials: Test with correct username and password to ensure that 
the login is successful when the input is valid.
2. Invalid Credentials: Test with incorrect username, incorrect password, or 
both to verify that the login fails when the input is invalid.
3. Edge Cases: Consider edge cases, such as empty username or password 
fields, and make sure the system handles them appropriately (e.g., 
providing the correct error messages).
Unit Test Project Setup
1. Before starting the test, ensure that the proprieties of two projects in 
the same solution have the same setup and necessary packages of 
dependencies.
• LogInPage_UnitTest project: NpgSql(7.0.6)
• LogIn_UnitTest project: 
NpgSql(7.0.6), Nunit(3.13.3),
NUnit3TestAdaper(4.4.2), 
Microsoft.NET.Test.Sdk(17.5.0),
coverlet.collector(3.2.0)
2. Start the back-end unit test app by clicking the “Run” command.
User interface
Unit test result
Project Setup: 
When preparing to deliver the Bubble Teahouse Management System to a client, it 
is essential to ensure a smooth setup process. Project setup instructions, including 
the necessary software and steps for installation are provided below.
Prerequisites:
Before setting up the project, the following prerequisites need to be met:
Database Version:
• PostgreSQL version 6.21 (or any compatible version).
Development Environment:
• Visual Studio 2019 (or any compatible version).
Frameworks and Technologies:
• C # with WPF .Net Framework 4.7.2 (for the back end).
Dependencies:
• Ensure that all project dependencies are installed. 
Project Setup Steps:
Database Setup:
• Install PostgreSQL version 6.21 or a compatible version on the client's 
machine.
• During installation, we will be prompted to set a password for the database 
superuser (Postgres). Remember this password as it will be required later.
• Choose the components we want to install. The default settings are usually 
sufficient for a basic installation.
• Complete the installation process. Make sure to note the port on which 
PostgreSQL will run (default is 5432).
• Create a new database for the Bubble Teahouse Management System and 
restore the database backup provided with the project.
• Create a user and assign it to the newly created database.
• Create tables for the project, such as employee, inventory, and product 
tables.
Visual Studio Setup:
• Document the code and project structure to make it understandable for 
others or for future reference.
• Set up different build configurations for debugging and release. Ensure that 
the release build includes optimizations.
• Use the publish feature in Visual Studio or package it using tools like WiX for 
creating an installer.
• Download and install from the official Microsoft website Visual Studio 2019 
(or any compatible version).
• Share the installer package with the client. This could be via download link, 
USB drive, or any other distribution method.
• Open the Visual Studio project: BubbleTeaProject.
• Configure the connection string in the project's appsettings.json file to point 
to the client's SQL Server database.
• Build the solution and ensure that all NuGet packages are restored, such as 
NpgSql.
• Create desktop shortcuts or Start Menu entries for easy access.
• Test the application on the client machine to ensure it works as expected.
RESAT API Setup:
• Document API, providing details on available endpoints, expected request 
and response formats, and any authentication requirements.
• Generate a snapshot of our API documentation. This could be a 
downloadable file or hosted documentation accessible via a URL.
• Open the Visual Studio project: RestAPIBubbleTeatProject and 
WPFBubbleTeaProject.
• Test the API integration within the client application to ensure it 
communicates correctly with the server by running the two projects with 
start buttons and implementing all the methods. 
Testing and Troubleshooting Locally 
Bubble Tea App: 
1. Interact with our WPF user interface of the application to perform all the 
actions that involve the database operations.
2. Ensure that any database operations performed by our application locally 
(such as searches, inserts, updates, deletes and show all) are working as 
expected.
3. If there are issues, check the application logs or console output for any 
error messages.
4. Review the C# application code for any issues related to database 
interactions. Ensure that connection strings, queries, and ORM mappings 
are correct.
5. Verify that the database connection settings in our application (connection 
string, credentials) are accurate for the local database.
6. Ensure that the database schema matches the expectations of our 
application. Tables, columns, and relationships should align with what our 
application is expecting.
7. Use mock data or seed the client’s local database with test data to simulate 
various scenarios.
REST API:
1. Send requests to our API. Test various endpoints and methods (GET, POST, 
PUT, DELETE).
2. Examine the responses from our API. Ensure they match the expected 
behavior based on our API documentation.
3. If there are issues, check the console logs in Visual Studio or the terminal for 
any error messages.
4. Review our API code for any issues. Ensure that routes, controllers, and logic 
are correctly implemented.
5. Ensure that the database connection is properly configured.
6. Check our firewall settings to ensure that the API is allowed to run and 
receive requests locally.
By following these steps, the Bubble Teahouse Management System can be 
efficiently set up and configured on the client's machine or hosting environment 
for seamless operation and testing.
Work Progress in Future
There are several enhancements and additional functionalities that can be 
incorporated into the Bubble Teahouse Management System to improve its 
performance, user experience, and versatility.
Here are some potential features and developments that could be implemented 
soon:
• Shopping Cart Order Update: Customers can update their order by changing 
the quantity of items or adjusting customizations. Customers can remove 
items from the cart if they change their minds or no longer want a particular 
item. The system dynamically recalculates the total cost of the order based 
on any updates made in the cart.
• Employee Management: Track employee work schedules and monitor 
employee attendance.
• Mobile Application: Create a mobile app version of the system, allowing 
customers to place orders, directly from their smartphones. This mobile app 
could also provide push notifications for promotions and order updates.
• Integration with Delivery Services: Partner with food delivery services like 
Door Dash, Grubhub, or Uber Eats to enable online ordering and delivery 
from the teahouse. This integration would expand the customer base and 
increase sales.
• Inventory Forecasting: Implement an inventory forecasting system that uses 
historical data and real-time sales information to predict inventory needs. 
This would reduce waste and ensure that popular items are always in stock.
• Multi-Language and Currency Support: Cater to a broader customer base by 
adding multi-language support.
• Enhanced User Feedback: Provide customers with channels for feedback, 
including surveys and reviews, and enhance the system's ability to analyze 
and respond to this feedback.
• Automated Social Media Integration: Automatically post promotions, menu 
updates, and customer reviews on social media platforms to boost the 
teahouse's online presence and engagement.
These future enhancements will help the Bubble Teahouse Management System 
stay competitive, adapt to changing customer preferences, and continue providing 
excellent teahouse management and customer experience. It is important to 
regularly evaluate the system's performance and gather user feedback to prioritize 
these developments effectively.

# c67-brassandpoembook1-Lmanning1431
c67-brassandpoembook1-Lmanning1431 created by GitHub Classroom
Define the ProductType Class
a. Inside the ProductType.cs file, create a class named ProductType. b. Add the following property to the ProductType class:

Title (string): Represents the title of the product type.
Id (int) : Represents a unique Id for the product type
Define the Product Class
a. Inside the Product.cs file, create a class named Product. b. Add the following properties to the Product class:

Name (string): Represents the name of the product.
Price (decimal): Represents the price of the product.
ProductTypeId (int): Represents the id for the product's product type
Create the program loop
Declare a list of product types and a list of products. When creating the lists, add at least two product types and five products.
Display a welcome message for the application
Create a loop that asks the user to choose an option, and will continue running until the use selects 5, at which point the program will finish.
Implement the Menu System in Program.cs
Inside the Program.cs file , you will implement the following methods underneath the loop (detailed instructions for each below).

All of the methods should accept two parameters, in this order:

The list of products
The list of product types
To test whether these methods work, add logic to the program loop to call the appropriate method when a user chooses an option:

DisplayMenu

DisplayAllProducts

DeleteProduct

AddProduct

UpdateProduct

Implement the DisplayMenu Method
The DisplayMenu method should display the following options to the console:

1. Display all products
2. Delete a product
3. Add a new product
4. Update product properties
5. Exit
Implement the DisplayAllProducts Method
Iterate over the products and display each product's name and price on a new line in the console. Start the line with the number of that product in the List (have the list start with 1, not 0).
Add the product type title to the product display. HINT: You will need to use a Linq method to get the product type for each product.
Implement the DeleteProduct Method
Display the products and prompt the user to enter the number of the product they want to delete.
Remember that the list should start from 1.
Find the product with the provided number and remove it from the list of products.
Implement the AddProduct Method
Prompt the user to enter the name and price of the new product (in this order).
Display the ProductTypes and prompt the user to choose a type for the new product.
Create a new instance of the Product class using the provided information.
Add the newly created product to the list of products.
Implement the UpdateProduct Method
Display the products and prompt the user to enter the number of the product they want to update.
Find the product with the provided number and retrieve its reference.
Remember that the list should start from 1.
Prompt the user to enter the updated name, price and product type for the product (in that order). If the user presses enter without typing anything, leave the property unchanged.
Update the product's properties with the provided information.


# ISTA Project Step 2
---
#####Michelle Caballero
#####January 19, 2019

After two weeks of class my project aspirations were put into perspective. I 
realize how difficult it is to get a computer to do what you want it to do. I
now understand the concept of inputting data into an application and how in
actuality that data is stored. I understand once that data is stored there are
procedures necessary to retrieve that data, and also to manipulate the data.
That being said in order to eloquently exercise and display the skills I learned
I have to start with a basic project. I will be creating an online store
application. This project will allow me to create a database, manipulate the
database, use the database to process orders, and display that process through a
graphical user interaction, achieving my objectives of exercising, implementing,
and displaying my skills. This application will also achieve my objective of
helping others by creating it to help my father expand his business through an
online stores.

###Data Phase

From the concepts I learned so far, my understanding is that the different data
this application needs are;
+ Products Data
This would include the product id, name, description (color, dimensions, use,
category), price, and pictures.
+ Customer Information
This would include customer id, name, email, phone number, and address (street
address, city, state, country, zip code, etc.)
+ Order Information
This would include order id, products order information ( product id, name, price,
picture, quantity order, total price, etc.),  payment method, card payment method
information (name on card, card number, expiration date, cvc code, type of card,
zip code, etc.), routing payment method information (bank name, account number,
routing number, type of account, etc.), shipping information (name, street
address, city, state, country, zip code, etc.) shipping cost (shipping information,
associated cost depending on location(state), estimated arrival time depending on
product id, and shipping address).

###Programming Phase
The logic of my application is for users to view products available through a
display of the product name in text and a picture of the product. They can click
on product name text or the product picture for more information and options.
Once they click the product they will see product data (name, description (color,
dimensions, use, category), price, and multiple pictures from different angles.
There will be an add to cart button. The add to cart button will
add the product to a repository of products. The go to cart button will display
the repository of products and product information, add each products price and
display total, (warning will display with the text(this is not total price,
shipping price will be added when enter shipping address). There will be a order
now button that takes you to enter shipping information section, (not sure if I
want it to drop down on same display or take you to new display). User will enter
shipping information (name, street address, city, state, country, zip code, etc.)
user will click next. Next button will calculate new price with shipping, must
note that if there are multiple products that must be shipped separately then
shipping cost must be calculated for each individual product and then added
together and then added to price before shipping. After completing calculation
a display (not sure if I want it to drop down on same display or take you to new
display) of the new total price, and estimated arrival day. Place for user to
enter payment method will also display. User will be able to click on different
buttons for different payment methods. Once payment method is clicked. Display
will allow user to enter payment information. Once all payment information has
been entered user will click paynow button. Pay now will conduct transaction,
verify transaction was successful. If transaction was successful a receipt will
be created, stored, and displayed two buttons will display one allowing user to
print and the other allowing users to email it. Also if transaction was
successful, all order information, user information, payment information, shipping
information will be stored. If transaction is unsuccessful a message with text,
transaction failed will display two buttons will appear, button try again will
allow user to try transaction again, other button try other method will take
user back to payment method buttons.

###User Interface
I will be using a graphical user interphase (GUI) that will allow users to click
their way through process of ordering products.

First I will work on the database aspect. I will start this project by creating
product database, only input a hand full of products in order to facilitate
building rest of application, Then create the customer database and the order
database in order to input and store new users data. Second I will work on the
GUI aspect. I will create the graphical display of the products using the Products
database. I will then create the button's design and functionality in precedence
of which button the user interacts with first. I will then test each button to
ensure functionally of each is working appropriately. If all buttons work will
individually I will test if each button works on in conjunction. If they all
synchronize, I will then place test orders. Once test orders run appropriately.
I will continue to expand the products database, and start working or version
2.0.

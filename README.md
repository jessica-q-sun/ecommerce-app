# An E-Commerce App

An e-commerce web application that allows users to create an account, search books by name and category, browse related products, add and update books in the shopping cart, and checkout with credit card or PayPal. 

## Project Highlights

* Incorporated Braintree Gateway to allow users to pay using either PayPal or credit cards
* Designed flexible private and admin routes for role based access
* Implemented advanced searching/filtering based on book categories and price range
* Built Admin and User dashboard
* Implemented advanced CRUD with Products and Categories
* Achieved user profile and update ability
* Enabled authentication based on JWT
* Stored sold products record into the database for further processing
* Built scalable React App with proper layouts and routes
* Primary technology used: Node JS API, React JS, MongoDS, React Hooks, JWT

## Demo
### Home Page:
<image src="./demo/Home-page.gif" height="300"/>


### User can search books by title and category. If there's no match, a "no products found" message will show up:
<image src="./demo/Search-HandleError.gif" height="300"/>


### User can filter books by category and price range, then add a book to cart:
<image src="./demo/Shop-AddtoCart.gif" height="300"/>

### User can update the product quantity or remove the product from the shopping cart. User can then pay with a credit card:

<image src="./demo/ShoppingCart.gif" height="300"/>

### PayPal payment is also allowed:
<image src="./demo/PayPal-Payment.gif" height="300"/>

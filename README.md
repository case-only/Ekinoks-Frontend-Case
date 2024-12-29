# Ekinoks-Frontend-Case


Ekinoks Frontend Developer (React) Coding Challenge

You are expected to create a simple e-commerce web application using the Fake Store API and React.

You have 1 week to complete the challenge.


Requirements:

Your app should be able to complete the following tasks.


User authentication: 

Authenticate user using the "Login" route of the API, unauthenticated user will not be able to complete the checkout simulate process.


Product Listing:

List all products on index page using the API - (use pagination or infinite scroll for listing the products)

Filter products by category, sort('asc' - 'desc') and limit using related API routes

Show product details (title, image, price etc.) in modal or page, by clicking to product list item. 


Add to shopping cart:

 Add/remove items to the shopping cart. Show items count in cart and update synchronously.

 List products in shopping cart page and calculate total cost for payment process.

 Show product related infos in shopping cart list (title,price, image, description, etc.)

 Store shopping cart related data in Redux - Redux Toolkit (store persistent via localStorage etc.)

 

Simulate checkout:

Create checkout form which includes shopping cart products infos, shipping information, card detail.

Shipping informations -> (name, email, address, etc.)

Card informations -> (card number, expire date, CVC)

Simulate successful and failed form submit state (with alert, toaster component etc.)


Extras:

Create page for adding new product using related API route, and simulate create product.

Simulate product info update, in product detail page-modal, using related API route,

Simulate delete a product, using related API route,

Dark/Light theme support or language support (TR-EN)

Write a test case in react - preferably with (jest, react-testing-library)


Grading:

The grading of the app will be based off of three criteria:

30% - UI and UX

40% - Overall Design and Structure

30% - Data Management and Store


API Links:

https://fakestoreapi.com/docs


P.S:

You can use an UI library. The UI is left to your preference. Subjects such as being pleasing to the eye and being responsive will be a factor that we will consider.

Proper usage of React Hook API is a plus. (Custom Hooks usage etc.)

Do not overlook the Data management and store data sections. Don't lose 30 points for a very simple reason.

Please make sure that form input validations are correct. 

example: 

 - Card number field only allow number inputs, 

 - Paying attention required form fields, not submitting the form if there is a empty and required field

Please make sure that the data and error messages are correct.

Do not be complacent because the homework is simple. Please include everything that should be in a real app. example: don't submit an app without pagination on listing pages.

Please use Git (local repository or Github, Gitlab etc.) for development and do not forget to publish a working version of the application on a site.

Please send a message for your questions.

---
layout: essay
type: essay
title: "Assignment 3 Checkpoint"
# All dates must be YYYY-MM-DD format!
date: 2022-11-28
published: true
labels:
  - MIS
  - Prototype
---
## Show what each page will look like. The pages do not have to be “functional” but the design should clear.

Click [here](https://dport96.github.io/ITM352/morea/150.Assignment2/experience-Assignment2_retrospective.html) to watch a brief presentation of my desired layout and functionality of my e-commerce website.

## Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.

My shopping cart is a separate page that can be accessed through the side bar of the home and products pages. Each of the products pages will have an add to cart button where they can add items to their cart. On the cart page itself, I will eventually add a button for users to add quantities, and remove quantities from their cart. There will be two buttons at the button my this page one to continue shopping and the other to continue with their purchases which will bring them to the invoice page.

## Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.

Sessions will be utilized in my assignment 3 to manage my shopping cart information and store quantity data. The value of each product type key will be the quantities for each of the products in an array format. For instance, if a user wants to add products from a variety of products pages the item data in the session will look like this:
{ Succulents: [ 1, 0, 1 ], Snake Plant: [ 2, 1, 0 ] }

## How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?

I will avoid access to my application when the user has not logged in or registered yet by using cookies. When a user purchases an item through the shopping cart, the server will check if the user has a cookie.  If the user does have a cookie and is logged in, they will be directed to the invoice however if user does not have a cookie , the user will be taken to the login page to sign in or will have to create an account. A security concern with this way is that cookies can be accessed and modified.

## Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)

Upon a successful login I will include the email of the username in the invoice message. Also in the thank you page, I will include the user's name and email address to verify their purchases. I will do this by using the user_data stored in the cookie in the initial log in.

## If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?

I am not working with a partner

##  How are you approaching Assignment 3 differently than Assignment 2?

Compared to assignment three I am taking more time to think about my plan and create a design before starting the actual project. The assignment 3 checkpoint helped me lay everything out because I am not yet completed with everything. I am doing my best to not stress myself out over the small things like I have been doing with assignment 2 and 1. 






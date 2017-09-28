# Takehome Test (Full-Stack)

## Overview

This is a takehome test for candidates applying for a full-stack developer
position at ShopPad. It contains two sections: "Backend" and "Frontend", which
together include a series of tests involving HTML, CSS, JavaScript, and PHP.
 
Feel free to solve these questions however you see fit, using whatever coding
style or third-party libraries you think are appropriate.

To start the test, simply clone this repo and make your edits locally.

## Frontend

For the frontend portion of the test, we have a file called
"responsive-layout.html" which contains some boilerplate HTML with 6 div
elements. There are 3 features we'd like to add:

1. Add CSS to create a responsive layout that will display one column on mobile
devices, two columns on tablet devices, and three columns on desktops.
2. Add JS to apply alphabetical sorting of the div elements when the "Sort"
button is clicked.
3. Add JS to apply a random shuffle to the div elements when the "Shuffle"
button is clicked.

Feel free to use third-party libraries at your own discretion.

## Backend

For the backend portion of the test, we have an empty PHP file called
"inventory.php". We'd like to write some code that achieves the following:

1. Make an authenticated request to the dev store's Admin API
2. Retrieve all product data and calculate the sum of all available inventory
for all products (and their variants)

The file is empty on purpose, so feel free to structure the code however you
prefer and use third-party libraries at your own discretion.

### Shopify Store and API Information

* **Shopify Dev Store URL:** https://shoppad-candidate.myshopify.com/collections/all
(password: "candidate")
* **Shopify Admin API Documentation:** https://help.shopify.com/api/reference/product
* **API Key:** (Provided Via Email)
* **API Password:** (Provided Via Email)

There's also a file called "price-sum.php" which contains a small coding
challenge:

Given a list of prices and a target sum, write a function that returns true if
the list of prices contains 2 prices that add up to the target sum.

For more details, consult the comments in price-sum.php.

## Submitting Your Code

Once you've completed the test, please compress your files (via zip or tar) and
return them as an email attachment in reply to your test invite. We'd like the
code in your submission to remain private, so please avoid committing or pushing
the code publicly.

Once we receive it, a member of our team will review and we'll get back to you
as soon as possible.

Thanks!

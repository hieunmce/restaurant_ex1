# CoderRestaurant Website

**Coder Restaurant** is a Ruby on Rails restaurant website let users order foods.

Submitted by: **HieuNM6**

Time spent: **18** hours spent in total

URL: https://desolate-eyrie-45495.herokuapp.com/

## User Stories

### Required:

* [x] User must be able to go two pages: Menu, and Contact Us.
* [x] User can see the address and phone number on the contact us page.
* [x] User can see a basic google map on the Contact Us page.
* [x] User can navigate to a menu page with four sections:
  * [x] Breakfast
  * [x] Lunch
  * [x] Dinner
  * [x] Drinks
* [x] User should see at least 5 food items in each section.
* [x] Each food item should have the following fields:
  * Name (Canh Chua)
  * Description (Delicious fish soup)
  * Price (VND)
  * Section - Breakfast, Lunch, Dinner, Drinks
  * Image URL - do a google search or use LoremFlickr: http://loremflickr.com/320/240/canhchua
* [x] User should be able to filter by section of Breakfast, Lunch, Dinner, or Drinks and see only the relevant items.
* [x] User can sort menu items by “alphabetical”, “price low to high”, and “price high to low”.
* [x] User should be able to get for a menu item and see results.
* [x] Clicking on an item in the menu brings up its detail, where you see the description and a larger picture.
* [x] User can click “order” on a menu item to go to a “Create Order” page.
* [x] User is able to fill in their name, phone number, and address.
* [x] User is taken to a “Thank you for your order page” that lists the name of item, the total cost (delivery should cost 20,000 VND), the user’s name, the user’s address, and the time the order was created in human-readable format (for example, Tuesday, December 1, 15:25).

### Optional:

* [x] User can also filter by type of Cuisine.
* [x] User can see how many times each menu item has been viewed, and sort items by “most viewed”.
* [x] User can leave a review (1-5 stars) for each dish, along with a text review.
* [x] User can see reviews and an average review score.
* [x] User can input "CODERSCHOOL" as a coupon code on the order page, which should give a 50% discount off of the order.
* [x] User can order more than one dish at a time.
* [ ] User receives an email upon placing an order.
* [ ] The Restaurant (you) receives an email or SMS when a User places an order. Try Twilio if you’d like a SMS API. Use Promo Code CodeSchool15 for $30 free credit.

The following **additional** features are implemented:

* [x] User can remove item on shopping cart.

The following **known issues**:

* Create order form, and commit review form not have any validation.
* Can't order one item many times, (could order many times using url but one time press removes will remove all items have the same id)

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![Video Walkthrough](https://raw.githubusercontent.com/HieuNM6/restaurant_ex1/57642b3995069abc64d6340a253772b2d142ca64/screencast.gif)


## Notes

I focus on some feature and then it make me out of time because of that I haven't added any validation for model, relayout, email feature,... Last time I will overcome my problem.

## License

    Copyright [2016] [HieuNM6]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

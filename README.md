# [Nord Snowboard](https://snowboard-new-latest.herokuapp.com/)


Are you a Scandinavian looking for the latest and greatest snowboard equipment? You've come to the right place! [Nord Snowboard](https://snowboard-new-latest.herokuapp.com/) is the place to shop. This is a "Proof of concept" webstore with the goal to attract investors and licenced dealers to take part in the company whose goal it is to provide snowboard/winter equipment primarily to Scandinavians.

Scandinavia is home to a disproportionate amount (considering the size of the countries within it) of the worlds best professional snowboarders. But there is virtually nowhere for one to shop online and have the goods sent out from within Sweden or Norway, therefore increasing the cost of shipping and creating a higher carbon footprint. The goal of Nord Snowboard is to have warehouses within Sweden and Norway to speed up delivery, make a demo program viable and to be better for the enviroment!

---

## Table of Contents
1. [**UX**](#ux)
    - [**User Stories**](#user-stories)
      
2. [**Features**](#features)
    - [**Existing Features**](#existing-features)
    - [**Features Left to Implement**](#features-left-to-implement)

3. [**Technologies Used**](#technologies-used)
    - [**Front-End Technologies**](#front-end-technologies)
    - [**Back-End Technologies**](#back-end-technologies)

4. [**Testing**](#testing)
    - [**Validators**](#validators)
    - [**Compatibility**](#compatibility)

5. [**Credits**](#credits)
    - [**Content**](#content)
    - [**Media**](#media)
    - [**Code**](#code)

---

## UX

This project is part of my [Code Institute](https://codeinstitute.net/) Full Stack Software Development studies, specifically the **E-commerce Applicationst** module. 

I have decided to build a snowbord webstore for many of the same reasons listed above.

### User Stories

"**_As a user, I would like to_** _____________________________"

:white_check_mark: *denotes items that have been successfully implemented*

- :white_check_mark: *view the site* from **any device** *(mobile, tablet, desktop)*.
- :white_check_mark: *view all products* as a **Guest**.
- :white_check_mark: *create* my **own profile**.
- :white_check_mark: *create* my **own password**
- :white_check_mark: be able to **add to cart**.
- :white_check_mark: be able to **add coupon**.
- :white_check_mark: be able to **get refund**.
- :white_check_mark: be able to **add coupon**.
- :white_check_mark: be able to **make payment**.
- :white_check_mark: be able to **see order summary**.

##### back to [top](#table-of-contents)

---

## Features

Features I've kept pretty straight forward and standard to an e-store. From personal experience and after asking some friends most agree that extra "features" when shopping don't enhance the experience.

### Existing Features

**Register Account**
- Anybody can register for free and create their own unique account. I have built-in authentication and authorization to check certain criteria is met before an account is validated. All passwords are hashed for security purposes!

**Log In to Account**
- For existing users, I have more authentication and authorization incorporated to check that the hashed passwords and username match the database.

**Change Password**
- Users can update their passwords from their profile page, after first validating their existing password.

**Log Out of Account**
- Users can easily log out of their account with the click of a button.

**Search Product**
- If a user would like to search for something specific.

**Add to Cart**
- When a user want to add an item to thier shopping cart

**View Cart**
- User can see the item they just added to the cart

**Continue Shopping**
- Option to continue shopping

**Checkout**
- Option to checkout.


**Remove from Cart**
- If a user no longer want to buy an item they can remove it from the shopping cart.

### Features Left to Implement

In an ideal world, there are a couple items that I would've loved to have completed as well, but just didn't have the time or knowledge just yet as to how to implement these features.

**A Landing page with links/promotions to social events**
- The Snowboarding community is strong and helping arrange and promote social event IRL and online. As this page is just "proof of concept" there are no event at the moment to promote.

**More and wider range of products to sell**
- A larger and wider range of products to sell. At the moment Nord Snowboard has no products and no warehouse so it was unneccasary to "pretend" to be selling products it doesn't have. At the moment it is just showing the backend is sound.

##### back to [top](#table-of-contents)

---

## Technologies Used

- [VS Code](https://code.visualstudio.com/) - Used as my primary IDE for coding.
- [GitHub](https://github.com/) - Used as remote storage of my code online.
- [Photoshop CS6](https://www.adobe.com/Photoshop) - Used for editing images.

### Front-End Technologies

- [HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - Used as the base for markup text.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3) - Used as the base for cascading styles.
- [jQuery 3.4.0](https://code.jquery.com/jquery/) - Used as the primary JavaScript functionality.

### Back-End Technologies

- **Flask**
    - [Flask 1.0.2](http://flask.pocoo.org/) - Used as a microframework.
    - [Flask Blueprints](http://flask.pocoo.org/docs/1.0/blueprints/) - Used to split the python code for routes.
    - [Flask Talisman](https://github.com/GoogleCloudPlatform/flask-talisman) - Used for security headers (HTTPS vs HTTP).
    - [Jinja 2.10](http://jinja.pocoo.org/docs/2.10/) - Used for templating with Flask.
    - [Werkzeug 0.16](https://werkzeug.palletsprojects.com/en/0.16.x/) - Used for password hashing, authentication, and authorization.
- **Heroku**
    - [Heroku](https://www.heroku.com) - Used for app hosting.
- **Python**    
    - [Python 3.6.7](https://www.python.org/) - Used as the back-end programming language.
    - [MongoDB Atlas](https://www.mongodb.com/) - Used to store my database in the 'cloud'.
    - [PyMongo 3.8.0](https://api.mongodb.com/python/current/) - Used as the Python API for MongoDB.
    - [Python Slugify 3.0.2](https://pypi.org/project/python-slugify/) - Used to generate user-friendly URLs.
    - [Python dotenv](https://github.com/theskumar/python-dotenv) - Used to get/set values in `.env` file.
- **Django Debug Toolbar** 
##### back to [top](#table-of-contents)

---

## Testing

**Creating an Account**

I've created my own personal account, along with the master *Admin* account. In addition to these two primary accounts, I've tested with about 20 fake accounts in order to confirm authentication and validation worked as expected.

**Add | Remove from cart**

Self explanatory really.

**Checkout, Purchace**

Also self explanatory.

### Validators

**HTML**
- [W3C HTML Validator](https://validator.w3.org) No errors.

**CSS**
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - Perfecto

```css
.collapsible-collection li:nth-child(odd):not(#search_form li) {
    background-color: rgba(var(--purpleLight5), 0.75);
}
.collapsible-collection li:nth-child(even):not(#search_form li) {
    background-color: rgba(var(--pinkLight5), 0.75);
}
```

- **Same color for background-color and border-bottom-color** - The code below overrides the Materialize color for the checkbox animation effect, so the validator thinks this is an error, but is correct in order to override the color with my own.

```css
[type="radio"].with-gap:checked + span:after
[type="radio"]:checked + span:after
```

**JavaScript**
- [JShint](https://jshint.com/)
    - :)

**Python**
- [PEP8 Online](http://pep8online.com/)
    - All `.py` files are completely PEP8 compliant!

### Compatibility

To ensure a broad range of users can successfully use this site, I tested it across the 6 major browsers in both desktop and mobile configuration.

- Chrome *v.74*
- Edge *v.18*
- Firefox *v.67*
- Safari *v.12*
- Opera *v.56*
- Internet Explorer *v.11*

For testing compatibility, I created a testing matrix to test across multiple devices and browsers. The test matrix can be found [here](app/testing/test-matrix.png). A brief overview:

##### back to [top](#table-of-contents)

---

## Credits

### Content

- [*"How to Write a Git Commit Message"*](https://chris.beams.io/posts/git-commit/) by **Chris Beams** (*as recommended by Code Institute assessors on previous projects*)

### Media

Sources of the images used on this site:

- [Blue Tomato](https://www.blue-tomato.com/)

### Code

- [freeCodeCamp](https://www.freecodecamp.org/)

##### back to [top](#table-of-contents)

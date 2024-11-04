![Teaser](./images/teaser.png)

**LindholmenEats** is a user-friendly restaurant app for ordering food. Enjoy easy access to a variety of restaurant offerings all in one place!

## Pages

* **Home:** landing page with LindholmenEats banner, and navigation links for the customer
* **Menu:** a page containing a scrollable list of food items with images, prices, and their descriptions, customers can order from here using the shopping cart
* **Signup:** customers can optionally create an account
* **Login:** customers can optionally login
* **User Info:** a page which allows logged in users to modify their account details
* **About:** Story of LindholmenEats
* **Location:** Location of restaurant from Google Map api
* **Career:** Careers page
* **Data:** Information about how we process user data

## Getting started

```bash
# Clone repository
git clone git@git.chalmers.se:courses/dit342/group-25-web.git

# Change into the directory
cd group-25-web

# Setup backend
cd server && npm install
npm run dev

# Setup frontend
cd client && npm install
npm run serve
```

# Create .env file in root folder of project (not the server folder)
Place the following in the .env file:
```
MONGODB_URI=mongodb+srv://USERNAME:PASSWORD@cluster0.ADDRESS.mongodb.net/restaurant-app
PORT=3001
```
Replace USERNAME, PASSWORD, ADDRESS according to our MongoDB Atlas instance.

## Entity-Relationship (ER) Diagram

![ER Diagram](./images/er_diagram.png)

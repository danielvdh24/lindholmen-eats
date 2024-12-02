<div align="center">
    <img src="https://github.com/user-attachments/assets/531ae39b-be26-4622-88ff-745cd2b8e583" height="370px">
</div>

LindholmenEats is a web-based application for ordering food - built with Vue.js for a responsive and dynamic user experience. The web app leverages MongoDB to store food items, order details, and user data while handling requests for retrieving menu items and processing orders to deliver a seamless customer experience.

## Pages

* **Home:** landing page with LindholmenEats banner, and navigation links for the customer
* **Menu:** a page containing a scrollable list of food items with images, prices, and their descriptions, customers can order from here using the shopping cart
* **Signup:** customers can optionally create an account
* **Login:** customers can optionally login
* **User Info:** a page which allows logged in users to modify their account details
* **About:** story of LindholmenEats
* **Location:** Location of restaurant from Google Map api
* **Career:** Careers page
* **Data:** Information about how we process user data

## Getting Started

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

## Set Up the .env
Place the following in the .env file:
```
MONGODB_URI=mongodb+srv://USERNAME:PASSWORD@cluster0.ADDRESS.mongodb.net/restaurant-app
PORT=3001
```
Replace USERNAME, PASSWORD, ADDRESS according to our MongoDB Atlas instance.

## Entity-Relationship (ER) Diagram

<img src="./images/er_diagram.png" alt="ER Diagram" height="400">

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

## Set Up Environment Variables

1. Create a `.env` file in the root directory of your project.

2. Add the following environment variables:

   ```env
   MONGODB_URI=mongodb+srv://USERNAME:PASSWORD@cluster0.ADDRESS.mongodb.net/restaurant-app
   PORT=3001
   ```
3. Replace the placeholders with your actual MongoDB Atlas credentials:

   - **USERNAME**: Your MongoDB username

   - **PASSWORD**: Your MongoDB password

   - **ADDRESS**: Your MongoDB cluster address



Ensure that your `.env` file is included in `.gitignore` to prevent exposing sensitive credentials.

## Entity-Relationship (ER) Diagram

<img src="./images/er_diagram.png" alt="ER Diagram" height="400">

## Contributers
<table>
  <tr>
    <td align="center"><img src="https://secure.gravatar.com/avatar/3056b6827d3d959ea87306c4d2dd0c6a?s=800&d=identicon" width="100px;"/><br/><sub><b>Daniel Van Den Heuvel</b></sub><br>@danielvh24</td>
    <td align="center"><img src="https://secure.gravatar.com/avatar/3271ba4e481b7c393b650b96a17344d0?s=800&d=identicon" width="100px;"/><br/><sub><b>Kai Rowley</b></sub><br>@rowley</td>
    <td align="center"><img src="https://git.chalmers.se/uploads/-/system/user/avatar/3455/avatar.png?width=400" width="100px;"/><br/><sub><b>Nasit Vurgun</b></sub><br>@nasit</td>
  </tr>
 </table> 

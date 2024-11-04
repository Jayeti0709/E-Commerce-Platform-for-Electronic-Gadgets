https://user-images.githubusercontent.com/84639970/226336865-730156f4-196f-4787-bb6b-2c5ecf09a123.mp4

# Project Overview
This project is a full-fledged e-commerce website designed to provide a seamless and user-friendly shopping experience. Developed with a robust tech stack, the platform is designed to handle a diverse range of products and services, offering a marketplace where businesses and individuals can list, manage, and sell products. Our website prioritizes both the buyer's and seller's needs by ensuring an efficient, secure, and engaging environment.


# Table Of Contents
- Technologies Used
- Key Features and Functionalities
- Installation and Setup
- Libraries
- Project Goals
- Future Enhancements
- Learn More

# Technologies Used
- **Frontend**: React.js
  
  Utilized for creating a dynamic, responsive, and interactive user interface.
- **Backend**: Node.js and Express.js
  
  Chosen for their speed and scalability, allowing complex server-side operations.
- **Database**: MongoDB
  
  A cloud-based, flexible, and scalable database for handling product catalogs, user data, and order details.

# Key Features and Functionalities

### For Customers:
- **Product Catalog**: Browse a variety of products across categories.
- **Add to Cart**: Easily add desired items to the shopping cart for later checkout.
- **Buy Now**: Quick purchase option for users wanting immediate transactions.
- **Real-Time Price Calculation**: Dynamic calculation of total costs as items are added to the cart.
- **Order Management**: Track and manage orders from placement to delivery.
- **Automatic Cart Clearing**: Cart is emptied upon successful checkout to streamline user experience.
  
### For Administrators:
- **Order Tracking**: Comprehensive view of all orders for efficient management.
- **Product Management**: Ability to add, edit, or remove products to keep the inventory current.
- **Inventory Control**: Flexibility to introduce new products and remove obsolete items to maintain a contemporary catalog.

# Installation and Setup

### Backend

- you have to enter the backend folder by typing `cd backend` in the terminal
- In the project directory,Install libraries by typing `yarn`
- Open a new file named .env

```environment
    MONGO_URI=mongodb+srv://user:passworrd@seyit.jwhpjae.mongodb.net/?retryWrites=true&w=majority
    JWT_SECRET=sdgkMKEVlm3v23kl_n423vGG3b_TVnm234xnv23
    JWT_REFRESH_SECRET=rerv1jv15v1CVBnasd23jnv1j3123nvrqwr23
```

- and type your mongodb URI
- Then Run backend project with `yarn dev`

---

### Frontend

- you have to enter the frontend folder by typing `cd frontend` in the terminal
- In the project directory,Install libraries by typing `yarn`
- Then Run backend project with `yarn start`
- You can reach the project from [localhost:3000](http://localhost:3000/)

---

# Libraries

### backend

- accesscontrol
- bcrypt
- boom
- cors
- dotenv
- express
- ioredis
- joi
- jsonwebtoken
- mongoose
- sucrase

### frontend

- @chakra-ui/react
- antd
- axios
- formik
- framer-motion
- moment
- react-dom
- react-image-gallery
- react-query
- react-router-dom
- react-scripts
- web-vitals
- yup

### database

- MongoDB

---

# Project Goals

Our e-commerce platform aims to:

- Deliver a reliable, scalable, and engaging shopping experience.
- Provide a secure transaction environment.
- Empower administrators with powerful tools for product and order management.
- Cater to a wide audience by offering diverse product categories and streamlined processes.

# Future Enhancements

Potential future improvements include:

- **Enhanced Security**: Additional layers of security for payment processing.
Advanced Search and Filtering: Improved user experience for finding specific products.
- **User Profile Management**: Allow customers to create profiles and save past orders.
- **Recommendation System:** Use AI to recommend products based on user behavior and preferences.
  
## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

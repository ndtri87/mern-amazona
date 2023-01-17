    # MERN AMAZONA

    # Lessons
    1. Introduction
    2. Install Tools
    3. Create React App
    4. Create Git Repository
    5. Create List Products
    6. Add Routing
    7. Create Node.JS Server
        1. run npm init in root folder
        2. Update package.json set type: module
        3. Add .js to imports
        4. npm install express
        5. Create Server.js
        6. add start command as node backend/server.js
        7. require express
        8. Create route for / return backend is ready
        9. Move products.js from frontend to backend
        10. Create route for /api/products
        11. return products
        12. run npm start
    8. Fetch Products From Backend
        1. set proxy in package.json
        2. npm install axios
        3. use state hook
        4. use effect hook
        5. use reducer hook
    9. Manage State By Reducer Hook
        1. define reducer
        2. update fetch data
        3. get state from useReducer
    10. Add bootstrap UI Framework
        1. npm install react-bootstrap bootstrap
        2. update App.js
    11. Create Product and Rating Component
        1. Create Rating component
        2. Create Product component
        3. Use Rating component in Product component
    12. Create Product Details Screen
        1. Fetch product from backen
        2. Create 3 column for image, info and action
    13. Create Loading ad Message Component
        1. Create Loading component
        2. use Spinner component
        3. Create utils.js to difine getError function
    14. Implement Add To Cart
        1. Create React Context
        2. Define reducer
        3. Create store provider
        4. Implement add to cart button click handler
    15. Complete Add To Cart
        1. Check exist item in the cart
        2. Check count in stock in backen
    16. Create Cart Screen
        1. Create 2 columns
        2. Display items list
        3. Create action column
    17. Complete Cart Screen
        1. Click handler for inc/dec item
        2. Click handler for remove item
        3. Click handler for checkout
    18. Create Signin Screen
        1. Create Sign in form
        2. Add email and password
        3. Add signin button
    19. Connect To MongdoDB Database
        1. Create atlas mongodb database
        2. install local mongodb database
        3. npm install mongoose
        4. connect to mongodb database
    20. Seed Sample Data
        1. Create Product model
        2. Create User Model
        3. Create seed route
        4. Use route in server.js
        5. Seed sample product
    21. Seed Sample Users
        1. Create user model
        2. Seed sample users
        3. Create user routes
    22. Create Signin Backend API
        1. Create signin api
        2. npm install jsonwebtoken
        3. define generateToken
    23. Complete Signin Screen
        1. Handle submit action
        2. Save token in store and local storage
        3. Show user name in header
    24. Create Shipping Screen
        1. Create form inputs
        2. Handle save shipping address
        3. Add checkout wizard bar
    25. Create Sign Up Screen
        1. Create input forms
        2. Handle submit
        3. Create backend api
    26. Implement Select Payment Method Screen
        1. Create input forms
        2. Handle submit
    27. Create Place Order Screen
        1. Show cart items, payment and address
        2. Handle place order action
        3. Create order create api
    28. Implement Place Order Action
        1. Handle place order action
        2. Create order create api

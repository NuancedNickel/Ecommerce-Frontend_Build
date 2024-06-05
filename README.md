# Ecommerce Frontend 
This repository contains the frontend part of the Ecommerce project. The frontend is built using modern web development technologies 
and frameworks to provide a seamless and responsive user experience. The project is deployed on Vercel and can be accessed here.

# Deployment        
The frontend part of the project is deployed on Vercel. You can visit the live application [here](https://ecommerce-frontend-build.vercel.app/)

# Tech Stack
<p style="line-height: 2;">
React.js : A JavaScript library for building user interfaces.    <br>
        
Redux Toolkit : A predictable state container for JavaScript apps.   <br> 

RTK Query : A powerful data fetching and caching tool built on top of Redux Toolkit.    <br>

TypeScript : A typed superset of JavaScript that compiles to plain JavaScript.    <br>

Node.js : A JavaScript runtime built on Chrome's V8 JavaScript engine.    <br>

Express.js : A minimal and flexible Node.js web application framework.    <br>

MongoDB : A NoSQL database for modern applications.    
</p>


 # Installation and Setup
<p style="line-height: 2;">
--> Install Dependencies        <br>
        
To install the necessary dependencies, run the following command : 
<code>npm install</code>
</p>

<p style="line-height: 2;">
--> Run the Application        <br>
        
To run the application in development mode, use the following command : 
<code>npm run dev</code>
</p>

# Environment Variables
To configure the application, create a <code>.env</code> file in the root directory and add the following environment variables to use the app:       

<p style="line-height: 2.5;">
VITE_FIREBASE_KEY = <code>from firebase</code>        <br>
        
VITE_AUTH_DOMAIN = <code>from firebase</code>        <br>

VITE_PROJECT_ID = <code>from firebase</code>        <br>

VITE_STORAGE_BUCKET = <code>from firebase</code>        <br>

VITE_MESSAGING_SENDER_ID = <code>from firebase</code>       <br> 

VITE_APP_ID = <code>from firebase</code>        <br>

VITE_SERVER = <code>Your Backend Server URL</code>        <br>

VITE_STRIPE_KEY = <code>Stripe Publishable Key</code>        <br>

Replace the placeholder values with your actual Firebase and Stripe configuration details.
</p>

# Backend Repository
The backend part of this Ecommerce project handles the server-side logic, API endpoints, and database interactions. 
It is built with Node.js, Express, and MongoDB. You can find the [backend repository](https://github.com/NuancedNickel/Ecommerce-ServerBuild)
.

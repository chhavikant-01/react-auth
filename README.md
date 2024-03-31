# Login And Register With JSON Web Token - Authentication System


# Features
- User Registration: Allows new users to create an account.
- User Login: Enables users to log in with their credentials.
- JWT Authentication: Secures user sessions using JSON Web Tokens.
- Responsive Design: Ensures a great user experience across various devices.

# Technologies Used
Frontend:
- React.js: For building the user interface.
- Toastify: To display notifications and alerts.
- React Router DOM: For managing navigation in the application.
Backend:
- Node.js: As the runtime environment.
- Express: Web application framework for Node.js.
- MongoDB: Database to store user credentials and session data.

# Installation
1. Clone the repository:

```
git clone git@github.com:chhavikant-01/react-auth.git
```

2. Install dependencies:
Navigate to the project directory:
```
cd react-auth
```

3. Install backend dependencies:
```
npm install
```

4. Install frontend dependencies:

```
cd client
npm install
```

5. Configure MongoDB and JWT:
Create the .env file in the root directory with the following contents according to your MongoDB account

```
MONGO_URI=
JWT_SECRET=
```


6. Run the application:
Start the backend server:
```
node app.js
```

7. In a new terminal, start the frontend:
```
cd client
npm run dev
```

# Usage
After starting the application, visit http://localhost:5173 in your browser. Users can now register for a new account or log in using existing credentials.

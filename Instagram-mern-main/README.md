📸 Instagram MERN Clone

An Instagram-like social media application built using the MERN Stack.
This project supports user authentication, profile management, posts, follow/unfollow functionality, and user search.

🚀 Tech Stack
Frontend

React.js

Redux

Axios

React Router

Material UI

CSS

Backend

Node.js

Express.js

MongoDB

Mongoose

JWT Authentication

bcryptjs

Tools & Utilities

Git & GitHub

MongoDB (Local / Atlas)

Nodemon (optional)

✨ Features

User Signup & Login (JWT based)

User Profiles

Follow / Unfollow Users

Create & View Posts

Search Users

Protected Routes

Cookie-based Authentication

Responsive UI

🔧 Prerequisites

Make sure you have the following installed:

Node.js (v16+ recommended)

npm

MongoDB (local or Atlas)

Git

⚙️ Environment Setup
🔹 Backend Environment Variables

Create a file at:

backend/config/config.env


Paste the following:

PORT=4000

MONGO_URI=mongodb://127.0.0.1:27017/instagram_clone

JWT_SECRET=my_jwt_secret_123
JWT_REFRESH_SECRET=my_jwt_refresh_secret_123

CLIENT_URL=http://localhost:3000

EMAIL=userzyx01@xyz.com
PASSWORD=1skjsnksdsd

CLIENTID=dummy
CLIENTSECRET=dummy
REDIRECT_URL=http://localhost:4000/auth/google/oauth

NODE_ENV=development

🔹 Frontend Environment Variables

Create a file at:

frontend/src/.env


Paste the following:

REACT_APP_API_URL=http://localhost:4000
REACT_APP_GOOGLE_OAUTH_REDIRECT_URL=http://localhost:4000/auth/google/oauth
REACT_APP_GOOGLE_CLIENT_ID=dummy

▶️ How to Run the Project
🔹 Step 1: Clone the Repository
git clone https://github.com/Techdarshit/instagram-mini-clone.git
cd instagram-mini-clone

🔹 Step 2: Install Backend Dependencies
cd backend
npm install

🔹 Step 3: Start Backend Server
node server.js


Backend will run at:

http://localhost:4000

🔹 Step 4: Install Frontend Dependencies

Open a new terminal:

cd frontend
npm install

🔹 Step 5: Start Frontend App
npm start


Frontend will run at:

http://localhost:3000

🧪 Testing

Signup a new user

Login

Search users

Follow / unfollow

View profiles & posts

🛑 Known Limitations

Image upload is disabled (AWS removed for local setup)

Google OAuth is not configured

Email functionality is mocked

🧠 Learning Outcomes

Full-stack MERN development

Authentication & authorization

REST API design

Redux state management

Environment-based configuration

Debugging cloned projects

📌 Author

Darshit Punglia
GitHub: Techdarshit

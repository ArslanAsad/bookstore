## Installation

### 1. Clone the repository
```bash
git clone https://github.com/ArslanAsad/bookstore.git
cd bookstore
```

### 2. Install dependencies
```bash
cd backend
npm install
cd ../frontend
npm install
```

### 3. Environment variables
Create a .env file in the backend folder and fill in your details:
```.env
PORT=5000
MONGODB_URI=
JWT_SECRET=bookstoreislegit
JWT_EXPIRES_IN=7d
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
STRIPE_SECRET_KEY=
EMAIL_USER=
EMAIL_PASS=
CLIENT_URL=http://localhost:5173
```
Create a .env file in the frontend folder and fill in your Stripe public key:
```.env
VITE_API_URL=http://localhost:5000
VITE_STRIPE_PUBLIC_KEY=
```

### 4. Running the app locally
Start the backend:
```bash
cd backend
npm start
```
In a new terminal, start the frontend:
```bash
cd frontend
npm start
```
Now visit [http://localhost:5173](http://localhost:5173) in your browser.

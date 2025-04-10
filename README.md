### EmployWise Frontend Assignment

# Hosted Link: 

## 🚀 Features

✅ Login using mock credentials  
✅ Protected route with token authentication  
✅ List of users with responsive card UI  
✅ Pagination support  
✅ Edit user (first name, last name, email)  
✅ Delete user  
✅ Logout functionality  
✅ Mobile-responsive and clean UI

## 🧰 Tech Stack

- ⚛️ React (Vite)
- 📦 Axios
- 🔄 React Router DOM
- 🎨 Material UI
- 🌐 ReqRes API (Fake REST API)

## 🔐 Login Credentials (as per ReqRes API)

Email: eve.holt@reqres.in
Password: cityslicka

## 📦 Installation & Setup

### 1. Clone the repo

- git clone https://github.com/lakshay-2411/Employwise.git
- cd Employwise

### 2. Install dependencies

npm install

### 3. Run the development server

npm run dev

## 🔐 Route Protection

- After login, a token is stored in localStorage

- /userlist page is protected and redirect to / if no token is found

## ✅ Usage Flow

- Login with valid credentials

- On success, navigate to the user list page

- Click Edit to update a user’s details (name/email)

- Click Delete to remove a user

- Use the Logout button (top-right) to clear the session

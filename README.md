📝 Job Portal Management System

A full-stack web application that allows users to search, apply for jobs, and manage applications efficiently.

🚀 Features

✅ User Authentication – Secure login & registration (JWT-based).

✅ Job Search & Filtering – Search jobs based on title, location, and category.

✅ Application Tracking – Users can apply for jobs and track their status.

✅ Admin Dashboard – Manage job postings and user applications.

✅ Responsive UI – Mobile-friendly design with React.js.

✅ Real-time Notifications – Get updates on job applications.

🛠️ Tech Stack

Frontend: React.js, HTML, CSS, Bootstrap

Backend: Node.js, Express.js

Database: MongoDB (Mongoose ORM)

Authentication: JWT (JSON Web Tokens)

Deployment: Vercel (Frontend), Render/Railway (Backend), MongoDB Atlas

📂 Project Structure
📦 JobPortal  
 ┣ 📂 client (Frontend - React.js)  
 ┃ ┣ 📂 src  
 ┃ ┃ ┣ 📂 components  
 ┃ ┃ ┣ 📂 pages  
 ┃ ┃ ┣ App.js  
 ┃ ┃ ┗ index.js  
 ┣ 📂 server (Backend - Node.js, Express)  
 ┃ ┣ 📂 routes  
 ┃ ┣ 📂 models  
 ┃ ┣ server.js  
 ┃ ┣ database.js  
 ┃ ┗ .env  
 ┣ 📜 package.json  
 ┣ 📜 README.md  
 ┗ 📜 .gitignore  

💻 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/jyothikakokkula3/Job_Lane_App.git

cd job-portal

2️⃣ Install Dependencies

For Backend

cd server
npm install

For Frontend

cd client
npm install

3️⃣ Setup Environment Variables (.env)

Create a .env file inside the server folder:

PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/joblane
JWT_SECRET=your_secret_key

4️⃣ Run the Application

Start Backend

cd backend
npm run dev

Start Frontend 

cd frontend
npm start

🤝 Contributing

If you'd like to contribute, please fork the repository and create a pull request.

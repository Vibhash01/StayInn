🏨 StayInn – One-Stop Hotel Booking Platform

StayInn is a full-stack hotel booking platform where users can browse hotels, view details, and book stays with ease. It includes secure login/signup authentication, session management, a personalized user dashboard, and a modern responsive UI.



🚀 Features

🔑 Authentication – User login & signup with session management
👤 User Dashboard – View bookings, reviews, and personalized recommendations
🏨 Hotel Listings – Explore hotels with images, pricing, and locations
📍 Map Integration – Pinpoint hotel locations on an interactive map
💾 Add Listings – Admins/owners can add new hotel listings
⭐ Reviews & Ratings – Users can review and rate hotels
📊 Analytics Dashboard – Track views, bookings, and ratings
🌐 Multi-Currency Support – INR / USD toggle for global users
📱 Responsive Design – Works seamlessly across desktop and mobile


🛠️ Tech Stack
Frontend

⚡ React.js
 with Vite

🎨 Tailwind CSS
 for styling

🗺️ Leaflet.js
 for maps

🔄 Axios for API calls


Backend

⚙️ Node.js
 with Express.js

🗄️ MongoDB
 with Mongoose ORM

🔐 JWT-based authentication & session management


Project Structure 

StayInn/
 ├── Backend/
 │   ├── controllers/
 │   ├── models/
 │   ├── routes/
 │   ├── app.js
 │   ├── package.json
 │
 ├── Frontend/
 │   ├── public/
 │   ├── src/
 │   ├── vite.config.js
 │   ├── package.json
 │
 ├── README.md
 └── .github/workflows (CI/CD configs)


⚡ Getting Started
1️⃣ Clone the repository
git clone https://github.com/your-username/stayinn.git
cd stayinn

2️⃣ Setup Backend
cd Backend
yarn install   # or npm install
yarn start     # or npm run dev


Create a .env file in the Backend folder:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret

3️⃣ Setup Frontend
cd Frontend
yarn install   # or npm install
yarn dev

4️⃣ Access the app

Frontend: http://localhost:5173

Backend: http://localhost:5000



🤝 Contributing

Contributions are welcome!
Fork the repo
Create a new branch (feature-xyz)
Commit changes
Open a PR


📜 License

This project is licensed under the MIT License.

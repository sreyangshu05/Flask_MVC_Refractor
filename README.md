Flask User Management API 🚀
A clean and scalable Flask-based User Management API with MongoDB integration. This project follows a modular architecture, making it easy to understand, extend, and maintain.

Features ✨
✅ User Authentication – Secure password hashing and verification
✅ CRUD Operations – Create, Read, Update, and Delete users
✅ MongoDB Integration – Uses Flask-PyMongo for database management
✅ RESTful API Design – Follows best practices for API development
✅ Modular Structure – Organized into config, models, routes, and utilities

Installation & Setup ⚙️
1️⃣ Clone the Repository
sh
Copy
Edit
https://github.com/sreyangshu05/Flask_MVC_Refractor/new/master
cd Flask_MVC_Refractor
2️⃣ Create a Virtual Environment
sh
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
3️⃣ Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt
4️⃣ Configure Environment Variables
Create a .env file and define:

bash
Copy
Edit
SECRET_KEY=your_secret_key
MONGO_URI=mongodb://localhost:27017/your_database
5️⃣ Run the Application
sh
Copy
Edit
python run.py
Server runs on http://localhost:5000 🎯
API Endpoints 🔗
User Management
Method	Endpoint	Description
GET	/users	Get all users
GET	/users/<id>	Get a specific user
POST	/users	Create a new user
PUT	/users/<id>	Update user details
DELETE	/users/<id>	Delete a user

Technologies Used 🛠
🔹 Flask – Lightweight web framework
🔹 Flask-PyMongo – MongoDB integration
🔹 Werkzeug – Secure password hashing
🔹 dotenv – Environment variable management

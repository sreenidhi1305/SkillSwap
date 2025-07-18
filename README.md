SkillSwap – Peer Skill Matching & Chat Platform
SkillSwap is a full-stack web application that connects individuals for skill exchange. Users can list skills they possess and skills they wish to acquire, get matched with compatible peers, and communicate in real-time to facilitate skill-sharing.

✨ Key Features
User Authentication: Secure JWT-based authentication.

User Profiles: Comprehensive profiles with skills possessed and desired.

Automated Matching: Intelligent algorithm matches users based on complementary skills.

Skill Swap Requests: Send and receive requests with matched partners.

Real-Time Chat: Integrated WhatsApp-style chat with auto-refresh.

Modern UI/UX: Clean, intuitive, and fully responsive design with Tailwind CSS.

Local MySQL Backend: Robust data management using a local MySQL instance.

🛠️ Technologies Used
Frontend
React: Declarative UI library.

React Router: For navigation.

Tailwind CSS: Utility-first CSS framework.

Axios: HTTP client for API requests.

Backend
Node.js & Express: Scalable server-side application development.

Sequelize ORM: Simplifies database interactions.

JWT: Secure authentication.

CORS: Cross-Origin Resource Sharing.

Database
MySQL: Local relational database.

🚀 How to Run Locally
SkillSwap runs entirely on your local machine with a local MySQL database.

Prerequisites
Node.js (v16+)

MySQL installed and running

Step 1: Download & Extract the Project
Download the SkillSwap project as a ZIP file and extract its contents to your desired directory. Navigate into the extracted SkillSwap folder.

Step 2: Set Up MySQL Database
Create the database in your MySQL client (e.g., MySQL Workbench, command line):

Sequelize will automatically generate tables when the backend starts.

Step 3: Configure & Start Backend
Navigate to the backend directory:

Install dependencies:

Create a .env file in the backend directory with these environment variables. Replace the placeholder values with your actual MySQL credentials and a strong JWT secret.

Start the backend server:

The backend typically runs at http://localhost:5000.

Step 4: Configure & Start Frontend
Navigate back to the main project directory and then into the frontend directory:

Install dependencies:

Start the frontend development server:

The frontend application will open in your browser, typically at http://localhost:3000.

🎯 Application Workflow
Register: Create an account, listing your skills (have/want).

Dashboard: Automatically matched with compatible users.

Send Requests: Browse profiles and send skill swap requests.

Chat: Initiate real-time conversations once requests are accepted.

🎨 UI Highlights
Animated Homepage: Dynamic gradient background.

Dashboard: Modern design with glassmorphism effects and intuitive match cards.

Chat UI: Clean and functional real-time messaging.

Fully Responsive: Seamless experience across all devices.

🧪 Optional API Testing with Postman
POST /api/users/register: Register new user.

POST /api/users/login: Authenticate user.

GET /api/users/profile: Retrieve authenticated user's profile.

GET /api/users/match: Get matched users.

POST /api/requests/send: Send a skill swap request.

POST /api/chats/send: Send a message.

GET /api/chats/:partnerId: Retrieve chat messages with a partner.

💡 Future Enhancements
Voice messages

File sharing in chat

Notifications

Profile image uploads

🤝 Contribution
SkillSwap is an open-ended project, great for beginners. Feel free to fork, explore, and extend its functionalities for learning or your portfolio.

📄 License
This project is open-source and available for educational use. Please refer to the LICENSE file (if present) for specific licensing details.

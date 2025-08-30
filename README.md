 Chit-Chat Messenger (ReactJS + Firebase)

A real-time chat application built using ReactJS and Firebase.
The app allows users to sign up, log in, join or create chat rooms, and send/receive instant messages with secure authentication and real-time updates.

* Features

* Authentication – Sign up & log in with email and password (via Firebase Auth)

* Real-Time Messaging – Instantly send and receive messages with timestamps

* Chat Rooms – Create or join multiple chat rooms dynamically

* Responsive UI – Works on desktop, tablet, and mobile devices

* Firebase Backend – Authentication, Firestore Database, and Hosting integrated

* Auto Refresh – Chat panel updates automatically in real-time

* Tech Stack

Frontend: ReactJS, HTML, CSS, JavaScript (ES6)

Backend/Hosting: Firebase (Authentication, Firestore, Hosting)

Tools & IDEs: Node.js, NPM, Visual Studio Code

Installation & Setup

Clone the repository:

git clone https://github.com/<your-username>/chit-chat-messenger.git
cd chit-chat-messenger


Install dependencies:

npm install


Run the development server:

npm start


Build for production:

npm run build

⚙️ Firebase Setup

Create a Firebase project from Firebase Console

Enable Authentication (Email/Password method)

Create a Cloud Firestore Database

Get your Firebase config and add it to a .env.local file:

REACT_APP_API_KEY=your_api_key
REACT_APP_AUTH_DOMAIN=your_project.firebaseapp.com
REACT_APP_PROJECT_ID=your_project_id
REACT_APP_STORAGE_BUCKET=your_project.appspot.com
REACT_APP_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_APP_ID=your_app_id


Start the app: npm start

 Project Structure
src/
 ├── App.js              # Main application file
 ├── SignUp.js           # User registration
 ├── LoginForm.js        # User login
 ├── SendMessageForm.js  # Sending messages
 ├── SideBar.js          # Chat room management
 ├── Fire.js             # Firebase configuration
 ├── firebase.json       # Firebase hosting config
 └── .firebaserc         # Firebase project reference

 Testing Highlights

* User sign-up & login flow works with Firebase Auth

* Chat messages sync instantly across users via Firestore

* Users can create and join chat rooms dynamically

* Invalid login or short passwords are rejected properly

 Future Improvements

* File sharing (images, docs)

* OAuth login (Google, GitHub, etc.)

* End-to-end encryption for messages

* Push notifications for new messages

* Live Demo


 Authors

Ammiel Peters

Tuhin Barman

Niraj Uppadhya

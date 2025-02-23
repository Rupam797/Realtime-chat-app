# 📩 Realtime Chat App

A modern, responsive, and fully functional real-time chat application built with **React.js**, **Firebase**, and **Tailwind CSS**. This app includes user authentication, live messaging, and complete CRUD functionality, making it perfect for learning or deploying as a small-scale messaging platform.

## 🚀 Features

- **Authentication:** User signup, login, and logout using Firebase Auth (Email/Password, Google Sign-In).
- **Real-time Messaging:** Send and receive messages instantly with Firebase Firestore.
- **CRUD Operations:**
  - **Create:** Send new messages.
  - **Read:** Fetch and display messages in real-time.
  - **Update:** Edit your sent messages.
  - **Delete:** Remove unwanted messages.
- **Responsive UI:** Designed with Tailwind CSS for a clean, mobile-friendly interface.
- **Timestamps & User Info:** Messages include timestamps and sender details.

## 🛠️ Tech Stack

- **Frontend:** React.js
- **Backend/Database:** Firebase (Firestore, Realtime Database)
- **Authentication:** Firebase Auth
- **Styling:** Tailwind CSS

## 📂 Folder Structure

```
/chat-app
├── /src
│   ├── components/
│   │   ├── ChatRoom.js
│   │   ├── Message.js
│   │   └── Navbar.js
│   ├── App.js
│   └── index.js
├── .env (for Firebase config)
├── package.json
└── tailwind.config.js
```

## 🛠️ Installation & Setup

1. **Clone the Repository:**
```bash
git clone https://github.com/Rupam797/Realtime-chat-app.git
cd Realtime-chat-app
```

2. **Install Dependencies:**
```bash
npm install
```

3. **Configure Firebase:**
- Create a Firebase project.
- Enable Firestore Database and Authentication.
- Get your config object and add it to a `.env` file:

```
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

4. **Run the App:**
```bash
npm start
```

Access the app at: `http://localhost:3000`

## 🚀 Deployment

- Deploy on **Vercel** or **Firebase Hosting** for free, with simple deployment commands!

## 📸 Screenshots

(Include some screenshots or a demo GIF here)

## 🤝 Contributing

Pull requests are welcome! Feel free to fork the repo and submit PRs.

## 📜 License

This project is licensed under the **MIT License**.

---

Made with ❤️ by **Rupam797**

---

Does this look good to you? Or do you want me to tweak anything? Let me know! 🚀


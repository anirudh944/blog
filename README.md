
## 🧠 AI Enthusiasts Blog

A community-driven blog platform where AI enthusiasts can share articles, insights, and tutorials about artificial intelligence. Built with Firebase for seamless backend integration.

### 🚀 Features

- ✍️ Post and edit AI-related articles
- 🔍 Browse and search community submissions
- 🔐 User authentication (Firebase Auth)
- 📦 Real-time database with Firebase Firestore
- 📸 Optional image uploads for articles
- 📱 Responsive design for mobile and desktop

### 🛠️ Tech Stack

| Frontend | Backend | Database | Auth |
|----------|---------|----------|------|
| HTML/CSS/JS or React/Vue | Firebase Functions (optional) | Firebase Firestore | Firebase Auth |

### 📦 Installation

```bash
git clone https://github.com/your-username/ai-blog.git
cd ai-blog
npm install
```

### 🔧 Configuration

1. Create a Firebase project at [console.firebase.google.com](https://console.firebase.google.com)
2. Enable Firestore and Authentication
3. Replace Firebase config in your project:

```js
// firebaseConfig.js
export const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

### 🧪 Development

```bash
npm start
```

### 🚢 Deployment

You can deploy using Firebase Hosting:

```bash
firebase login
firebase init
firebase deploy
```

### 🤝 Contributing

Pull requests are welcome! If you'd like to contribute:

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/awesome-feature`)
3. Commit your changes (`git commit -m 'Add awesome feature'`)
4. Push to the branch (`git push origin feature/awesome-feature`)
5. Open a pull request


# Job Community App

A modern React application for job seekers and professionals to connect, discuss interview experiences, and share insights about companies.

## 🌟 Features

- 🎨 Modern UI with Dark/Light Mode
- 💬 Real-time Chat Rooms for Companies  
- 👥 User Profiles (Students & Professionals)
- 🔍 Company Search & Management
- 📱 Fully Responsive Design
- 🔐 User Authentication with Persistent Sessions
- 🚨 Interview Help Notifications

## 🚀 Live Demo

**Deployed App**: [https://nagalakshmikalluri.github.io/JobCommunityApp](https://nagalakshmikalluri.github.io/JobCommunityApp)


## 📱 Testing Real-time Chat

### Method 1: Multiple Devices
1. Open the deployed URL on **2 different devices** (phone + laptop)
2. **Register different users** on each device:
   - Device 1: Register as "Student" with college info
   - Device 2: Register as "Professional" with company info
3. **Join the same company** chat room on both devices
4. **Test messaging** between devices in real-time

### Method 2: Multiple Browsers/Windows
1. **Regular window**: Register as User 1 (Student)
2. **Incognito/Private window**: Register as User 2 (Professional)
3. **Join same company** chat room
4. **Test chat functionality**

### 🧪 Test Scenarios
- ✅ Send messages between different users
- ✅ Test student asking for interview help
- ✅ Test professional responding with advice
- ✅ Test browser notifications (allow when prompted)
- ✅ Test dark/light mode toggle
- ✅ Test responsive design on mobile devices
- ✅ Test user profile viewing
- ✅ Test "Keep me logged in" functionality

## 💻 Local Development

```bash
npm install
npm start
```

## 🏗️ Build for Production

```bash
npm run build
```

## 🛠️ Technologies Used

- **Frontend**: React 18, Redux Toolkit, Tailwind CSS
- **Real-time**: Socket.IO Client (simulated for demo)
- **Routing**: React Router DOM
- **Deployment**: GitHub Pages
- **CI/CD**: GitHub Actions

## 📁 Project Structure

```
src/
├── components/          # Reusable components
├── contexts/           # React contexts (Theme)
├── features/           # Redux slices
│   ├── auth/          # Authentication
│   ├── chat/          # Chat functionality
│   └── company/       # Company management
├── pages/             # Main pages
│   ├── Login.js
│   ├── Signup.js
│   ├── CompanyList.js
│   └── ChatRoom.js
└── styles/            # CSS files
```

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

<h1 align="center">Interviewly</h1>

## 🚨 Deployed Link
👉 [Live Demo](https://hirelens-n84wz.sevalla.app/#/)

<h1 align="center">✨ Full-Stack Real-Time Video Interview & Coding Platform ✨</h1>

![Demo App](/frontend/public/screenshot-for-readme.png)

---

## 📝 Overview
Interviewly is a full-stack, real-time platform for conducting technical interviews with live video, chat and collaborative code editing. It is designed for interviewers and candidates to interact seamlessly, solve coding problems together, and get real-time feedback in a secure, modern environment.

---

## ✨ Features
- 🧑‍💻 **VSCode-Powered Code Editor**: Collaborative, real-time code editing with syntax highlighting.
- 🔐 **Authentication via Clerk**: Secure login and user management.
- 🎥 **1-on-1 Video Interview Rooms**: High-quality video calls with screen sharing and recording.
- 🧭 **Dashboard with Live Stats**: Track session activity, performance, and more.
- 🔊 **Mic & Camera Toggle, Screen Sharing & Recording**
- 💬 **Real-time Chat Messaging**
- ⚙️ **Secure Code Execution**: Run code in an isolated environment with instant results.
- 🎯 **Auto Feedback**: Success/fail feedback based on test cases.
- 🎉 **Confetti & Notifications**: Celebrate success, get notified on failure.
- 🧩 **Practice Problems Page**: Solo coding mode for practice.
- 🔒 **Room Locking**: Only 2 participants per room for privacy.
- 🧠 **Background Jobs with Inngest**: Async task processing.
- 🧰 **REST API**: Built with Node.js & Express.
- ⚡ **Data Fetching & Caching**: Powered by TanStack Query.
- 🚀 **Deployed on Sevalla**

---

## 🛠️ Tech Stack

**Frontend:**
- React (with Vite)
- Tailwind CSS & DaisyUI
- Clerk (Authentication)
- @monaco-editor/react (Code Editor)
- @stream-io/video-react-sdk (Video Calls)
- @tanstack/react-query (Data Fetching)
- Axios

**Backend:**
- Node.js & Express
- MongoDB (via Mongoose)
- Clerk (Authentication)
- Inngest (Background Jobs)
- Stream (Chat & Video)
- Sevalla (Deployment)

---

## 📦 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/GoyalParas/Interviewly.git
cd Interviewly
```

### 2. Environment Variables

#### Backend (`/backend/.env`):
```env
PORT=3000
NODE_ENV=development
DB_URL=your_mongodb_connection_url
INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLIENT_URL=http://localhost:5173
```

#### Frontend (`/frontend/.env`):
```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_API_URL=http://localhost:3000/api
VITE_STREAM_API_KEY=your_stream_api_key
```

### 3. Install Dependencies

#### Backend
```bash
cd backend
npm install
```

#### Frontend
```bash
cd ../frontend
npm install
```

---

## 🚀 Usage

### Start the Backend
```bash
cd backend
npm run dev
```

### Start the Frontend
```bash
cd frontend
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🧩 Project Structure

```
Interviewly/
├── backend/
│   ├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── ...
├── frontend/
│   ├── src/
│   ├── components/
│   ├── Pages/
│   └── ...
├── package.json
└── README.md
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact & Support

- GitHub Issues: [https://github.com/GoyalParas/Interviewly/issues](https://github.com/GoyalParas/HireLens/issues)
- Maintainer: [Paras Goyal](https://github.com/GoyalParas)

---

<p align="center">Made with ❤️ by Paras Goyal</p>
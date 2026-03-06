# DevRelay - Free Real-time Chat & File Sharing

**No login required. No registration. Just chat.**

DevRelay is a free, instant messaging platform for developers and teams. Chat in real-time, share files up to 10MB, and collaborate without registration or login.

##  Features

-  **Real-time Messaging** - Instant chat with WebSocket technology
-  **File Sharing** - Share files up to 10MB (images, videos, documents, code)
-  **No Registration** - Start chatting immediately without login
-  **QR Code Sharing** - Easy room invitation via QR codes
-  **Markdown Support** - Format messages with Markdown
-  **Dark Mode** - Comfortable viewing in any lighting
-  **Mobile Responsive** - Works on all devices
-  **Private Rooms** - Create private rooms for secure conversations

## Tech Stack

-  **Frontend:** HTML, Tailwind CSS, Vanilla JavaScript
-  **Backend:** Node.js, Express.js
-  **Real-time:** Socket.IO
-  **Security:** Helmet.js
-  **Deployment:** Vercel

## Quick Start

### Local Development

```bash
# Clone the repository
git clone https://github.com/getsettalk/DevRelay.git
cd DevRelay

# Install dependencies
npm install

# Start the server
npm start

# Or with nodemon for development
npm run dev
```

Visit `http://localhost:3000` to access the app.



## How to Use

1. **Create a Room:** Enter your name and click "Join Room" or use the "Random" button to generate a room ID
2. **Join via QR:** Share the QR code with friends to let them join instantly
3. **Chat:** Start typing messages and press Enter to send
4. **Share Files:** Click the + button to attach files or drag & drop
5. **Markdown:** Use Markdown syntax for formatted messages

## Live Demo

Visit the live demo at: https://devrelay.onrender.com

## Environment Variables

For local development, create a `.env` file:

```env
PORT=3000
NODE_ENV=development
```

For production on Vercel, no additional environment variables are needed.

## 🔒 Security Features

- Content Security Policy (CSP) headers
- Input sanitization
- File type validation
- File size limits (10MB max)
- XSS protection

## 🐛 File Types Supported

- **Images:** JPG, PNG, GIF, WebP, SVG
- **Videos:** MP4, WebM, MOV
- **Documents:** PDF, Excel (XLS, XLSX)
- **Code Files:** JS, HTML, CSS, JSON, Markdown, Text

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.

## 👨‍💻 Author

- **Sujeet** - [@getsettalk](https://github.com/getsettalk)

---

**Made with ❤️ for developers everywhere**

#GTUinsta.com 

Here's a comprehensive **README.md** file for your GTU Insta GitHub repository. You can copy and paste this directly into your project's root directory:

```markdown
# 🎓 GTU Insta - Gujarat Technological University Service Portal

A comprehensive portal for GTU students featuring academic resources, community forums, and university updates with interactive 3D animations.

## ✨ Features

- 📚 **Academic Resources** (Syllabus, Papers, Study Materials)
- 💬 **Student Community** (Forums, Study Groups)
- 📅 **University Updates & Events**
- 📊 **Personal Dashboard** (Grades, Timetable)
- 🎨 **Interactive 3D Animations** (Using Canva/Lottie)
- 📱 **Fully Responsive Design**

## 🚀 Live Demo

Coming soon! 

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Framer Motion
- Lottie Animations

**Backend:**
- Node.js
- Express.js
- MongoDB

## 📦 Installation

### Prerequisites
- Node.js (v14+)
- MongoDB
- Git

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dk51islive/GTUinsta.git
   cd gtu-insta
   ```

2. **Set up backend**
   ```bash
   cd server
   npm install
   ```

3. **Set up frontend**
   ```bash
   cd ../client
   npm install
   ```

4. **Environment Variables**
   Create `.env` file in `server/`:
   ```
   MONGODB_URI=mongodb://localhost:27017/gtu-insta
   JWT_SECRET=your_secret_key_here
   ```

5. **Run the application**
   - In one terminal:
     ```bash
     cd server && npm start
     ```
   - In another terminal:
     ```bash
     cd client && npm start
     ```

## 🎨 Adding Canva 3D Animations

1. Export your Canva designs as Lottie JSON files
2. Place them in `client/public/assets/animations/`
3. Use in components:
   ```jsx
   import { Player } from '@lottiefiles/react-lottie-player';
   
   <Player
     autoplay
     loop
     src="/assets/animations/your-animation.json"
     style={{ height: '300px', width: '300px' }}
   />
   ```

## 📂 Project Structure

```
gtu-insta/
├── client/                  # React frontend
│   ├── public/              # Static files
│   ├── src/                 # Source code
│   │   ├── components/      # Reusable components
│   │   ├── pages/           # Page components
│   │   ├── styles/          # CSS/Tailwind files
│   │   ├── App.js           # Main component
│   │   └── index.js         # Entry point
├── server/                  # Node.js backend
│   ├── models/              # MongoDB models
│   ├── routes/              # API routes
│   ├── index.js             # Server entry
└── README.md                # This file
```

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📧 Contact

e-mail: hello.premierdm@gmail.com

Project Link: [https://github.com/dk51islive/gtuinsta](https://github.com/Dk51islive/GTUinsta). 

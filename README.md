# 🎮 Game Mini App

[![Stars](https://img.shields.io/github/stars/Dev_Scorpian/Game-MiniApp?style=social)](https://github.com/Dev_Scorpian/Game-MiniApp/stargazers)
[![Forks](https://img.shields.io/github/forks/Dev_Scorpian/Game-MiniApp?style=social)](https://github.com/Dev_Scorpian/Game-MiniApp/network/members)
[![Issues](https://img.shields.io/github/issues/Dev_Scorpian/Game-MiniApp)](https://github.com/Dev_Scorpian/Game-MiniApp/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/Dev_Scorpian/Game-MiniApp)](https://github.com/Dev_Scorpian/Game-MiniApp/pulls)

A modern, full-stack web application that integrates with Telegram, providing an engaging gaming experience through a mini app interface.

## 🌟 Features

- **Telegram Integration**: Seamless integration with Telegram Bot API
- **Modern Frontend**: Built with Vue 3 and TypeScript
- **Secure Backend**: ASP.NET Core with JWT authentication
- **Database Integration**: MySQL database support
- **Real-time Updates**: WebSocket support for live game updates
- **Responsive Design**: Mobile-first approach for optimal gaming experience

## 🛠️ Tech Stack

### Frontend
<div align="center">
  <img src="https://img.shields.io/badge/Vue.js-3.4.21-4FC08D?style=for-the-badge&logo=vue.js" alt="Vue.js">
  <img src="https://img.shields.io/badge/TypeScript-5.4.0-3178C6?style=for-the-badge&logo=typescript" alt="TypeScript">
  <img src="https://img.shields.io/badge/Vite-5.1.6-646CFF?style=for-the-badge&logo=vite" alt="Vite">
  <img src="https://img.shields.io/badge/Axios-1.6.8-5A29E4?style=for-the-badge&logo=axios" alt="Axios">
</div>

### Backend
<div align="center">
  <img src="https://img.shields.io/badge/.NET-7.0-512BD4?style=for-the-badge&logo=.net" alt=".NET">
  <img src="https://img.shields.io/badge/MySQL-8.0.29-4479A1?style=for-the-badge&logo=mysql" alt="MySQL">
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens" alt="JWT">
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram" alt="Telegram">
</div>

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- .NET 7.0 SDK or higher
- MySQL Server (v8.0.29 or higher)
- Telegram Bot Token

### Installation

1. **Clone the repository**
```bash
git clone [repository-url]
cd Game-MiniApp
```

2. **Frontend Setup**
```bash
cd frontend
npm install
npm run dev
```

3. **Backend Setup**
```bash
cd backend
dotnet restore
dotnet run
```

4. **Environment Configuration**
   - Create a `.env` file in the frontend directory
   - Configure `appsettings.json` in the backend directory with your database and Telegram credentials

## 🔧 Configuration

### Frontend Environment Variables
```env
VITE_API_URL=http://localhost:5000
VITE_TELEGRAM_BOT_USERNAME=your_bot_username
```

### Backend Configuration
Update `appsettings.json` with your settings:
```json
{
  "ConnectionStrings": {
    "MySqlConnection": "your_connection_string"
  },
  "JsonWebToken": {
    "Secret": "your_jwt_secret",
    "Issuer": "your_issuer",
    "Audience": "your_audience"
  },
  "Telegram": {
    "Token": "your_telegram_bot_token"
  }
}
```

## 📁 Project Structure

```
Game-MiniApp/
├── frontend/
│   ├── src/           # Source code
│   ├── public/        # Static files
│   └── images/        # Image assets
└── backend/
    ├── Controllers/   # API Controllers
    ├── Common/        # Shared components
    ├── Middlewares/   # Custom middlewares
    ├── Telegram/      # Telegram integration
    └── wwwroot/       # Static files
```

## 🔒 Security Features

- JWT-based authentication
- HTTPS enforcement
- CORS configuration
- Secure password hashing
- Rate limiting
- Input validation

## 🎯 Development Guidelines

1. **Code Style**
   - Follow TypeScript best practices
   - Use ESLint for frontend code
   - Follow C# coding conventions

2. **Git Workflow**
   - Create feature branches
   - Use meaningful commit messages
   - Follow semantic versioning

3. **Testing**
   - Write unit tests for critical components
   - Perform integration testing
   - Test Telegram bot interactions

## 📱 Mobile Optimization

- Responsive design for all screen sizes
- Touch-friendly interface
- Optimized performance for mobile devices
- PWA support

## 🔄 Deployment

### Frontend Deployment
```bash
cd frontend
npm run build
```

### Backend Deployment
```bash
cd backend
dotnet publish -c Release
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Telegram Bot API team
- Vue.js community
- ASP.NET Core team
- All contributors to this project

## 📞 Support

For support, please open an issue in the repository or contact the development team.

### Contact Information
- Telegram: [@Dev_Scorpian](https://t.me/Dev_Scorpian)
- GitHub: [Dev_Scorpian](https://github.com/Dev_Scorpian)

---

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2D9EF7&center=true&vCenter=true&width=435&lines=Made+with+%E2%9D%A4%EF%B8%8F+by+Mahyar Mortezaei" alt="Typing SVG" />
</div>

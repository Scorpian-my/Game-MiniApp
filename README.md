# 🎮 Game Mini App

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
- Vue 3
- TypeScript
- Vite
- Vue Router
- Axios for API calls
- Lodash for utility functions

### Backend
- ASP.NET Core
- Entity Framework Core
- MySQL Database
- JWT Authentication
- Telegram Bot API
- AutoMapper for object mapping

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

---

Made with ❤️ by [Scorpian] 

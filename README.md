# Inventory Management System

A comprehensive inventory management system designed specifically for boba tea shops, helping to track ingredients, manage suppliers, and optimize stock levels.

## 🚀 Features

- Real-time inventory tracking
- Supplier management
- Order processing
- Usage monitoring
- Automated alerts for low stock
- Reporting and analytics
- User role management

## 🛠️ Tech Stack

- **Backend:** Node.js, Express
- **Database:** PostgreSQL
- **Frontend:** React, Material-UI
- **Authentication:** JWT
- **API Documentation:** Swagger/OpenAPI

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v16 or higher)
- PostgreSQL (v13 or higher)
- npm or yarn
- Git

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/lindakw/ims-project.git
cd ims-project
Install backend dependencies:
cd backend
npm install
Set up environment variables:
cp .env.example .env
# Update .env with your configuration
Set up database:
npm run db:setup
Start the development server:
npm run dev
🗄️ Project Structure
ims-project/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── utils/
│   └── package.json
├── database/
│   ├── schemas/
│   ├── migrations/
│   └── seeds/
├── docs/
│   ├── database/
│   └── api/
└── README.md
🔑 Environment Variables
NODE_ENV=development
PORT=3000
DB_HOST=localhost
DB_PORT=5432
DB_NAME=boba_shop
DB_USER=postgres
DB_PASSWORD=your_password
JWT_SECRET=your_jwt_secret
📚 API Documentation
API documentation is available at /api-docs when running the server.

Key endpoints:

/api/auth - Authentication routes
/api/inventory - Inventory management
/api/suppliers - Supplier management
/api/orders - Order processing
/api/reports - Reporting endpoints
🧪 Running Tests
# Run unit tests
npm test

# Run integration tests
npm run test:integration

# Run with coverage
npm run test:coverage
🤝 Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
📝 Development Guidelines
Follow Conventional Commits for commit messages
Write tests for new features
Update documentation as needed
Follow the established code style
🔐 Security
All endpoints require authentication except /api/auth
Role-based access control implemented
Input validation on all endpoints
Rate limiting enabled
SQL injection protection
🚀 Deployment
Deployment instructions:

Build the application:
npm run build
Start production server:
npm start
📈 Roadmap
 Mobile application
 AI-powered inventory predictions
 Automated supplier orders
 Multi-location support
 Advanced analytics dashboard
⚖️ License
This project is licensed under the MIT License - see the LICENSE file for details.

👥 Authors
Linda K. Westphal - lindakw
🙏 Acknowledgments
📞 Support
For support, email lkwest.dev@gmail.com.

Made with ❤️ by Linda K. Westphal

```

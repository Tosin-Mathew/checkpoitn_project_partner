# TaskFlow - Collaborative Project Management Platform

## Overview
TaskFlow is a full-stack project management application built with the MERN stack (MongoDB, Express.js, React, Node.js). It enables teams to collaborate on projects, manage tasks, track progress, and communicate effectively.

## Features
- ✅ User Authentication & Authorization
- ✅ Project Creation & Management
- ✅ Task Assignment & Tracking
- ✅ Real-time Updates with WebSockets
- ✅ File Uploads & Attachments
- ✅ Progress Analytics & Reporting
- ✅ Team Collaboration Tools
- ✅ Mobile-Responsive Design

## Tech Stack
**Frontend:**
- React 18
- Redux Toolkit
- Material-UI
- Chart.js
- Socket.io Client

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Socket.io
- Multer for file uploads

**DevOps:**
- Docker
- GitHub Actions
- Azure Web Apps
- MongoDB Atlas

## Quick Start

### Prerequisites
- Node.js 18+
- MongoDB 6+
- Git

### Installation
1. Clone the repository:
\`\`\`bash
git clone https://github.com/yourusername/taskflow-app.git
cd taskflow-app
\`\`\`

2. Install dependencies:
\`\`\`bash
# Install server dependencies
cd server && npm install

# Install client dependencies
cd ../client && npm install
\`\`\`

3. Set up environment variables:
\`\`\`bash
# server/.env
MONGODB_URI=mongodb://localhost:27017/taskflow
JWT_SECRET=your_jwt_secret
PORT=5000
CLIENT_URL=http://localhost:3000
\`\`\`

4. Run the application:
\`\`\`bash
# Start backend (from server directory)
npm run dev

# Start frontend (from client directory)
npm start
\`\`\`

## API Documentation
See [API Documentation](./docs/API.md) for detailed endpoint information.

## Deployment
The application is configured for deployment on Azure Web Apps with MongoDB Atlas.

## Contributing
Please read [CONTRIBUTING.md](./docs/CONTRIBUTING.md) for details on our code of conduct and development process.

## License
This project is licensed under the MIT License.

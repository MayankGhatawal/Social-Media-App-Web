# Snapgram


Welcome to Snapgram, a social media platform built with the MERN stack (MongoDB, Express, React, Node.js) and TypeScript. Snapgram allows users to share photos and interact with others through comments and likes, providing a seamless social experience.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- User authentication and authorization (signup, login, logout)
- Post photos with captions
- Like and comment on posts
- Follow and unfollow users
- Real-time notifications
- Profile management

## Tech Stack
- **Frontend:**
  - Next.js
  - TypeScript
  - Redux
  - Material-UI

- **Backend:**
  - Node.js
  - Express
  - MongoDB
  - Mongoose
  - JWT (JSON Web Tokens) for authentication

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Node.js (>= 12.0.0)
- npm (>= 6.0.0) or yarn (>= 1.22.0)
- MongoDB (>= 4.0)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MayankGhatwal/social_media_app-main.git
   cd social_media_app-main
   ```

2. Install dependencies for the frontend and backend:
   ```bash
   # Navigate to the backend directory
   cd backend
   npm install
   # Navigate to the frontend directory
   cd ../frontend
   npm install
   ```

3. Create a `.env` file in the `backend` directory and add the following environment variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

## Usage
1. Start the backend server:
   ```bash
   cd backend
   npm run dev
   ```

2. Start the frontend development server:
   ```bash
   cd frontend
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:3000`.

## Project Structure
```plaintext
snapgram/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── utils/
│   ├── .env
│   ├── package.json
│   └── tsconfig.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── services/
│   │   ├── styles/
│   │   ├── utils/
│   │   ├── pages/
│   │   │   ├── api/
│   │   │   ├── index.tsx
│   │   │   ├── _app.tsx
│   │   │   ├── _document.tsx
│   │   ├── public/
│   │   ├── package.json
│   │   ├── tsconfig.json
├── README.md
└── .gitignore
```

## Contributing
Contributions are always welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
If you have any questions, feel free to contact us at [your-email@example.com](mailto:your-email@example.com).

Happy coding!

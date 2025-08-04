# Anymmes Platform

Anymmes is a modern web platform that allows users to send and receive anonymous messages. Inspired by platforms like ngl.link, Anymmes focuses on user privacy and a seamless user experience.

## Features

- **Anonymous Messaging**: Users can send and receive messages without revealing their identity.
- **User Authentication**: Secure registration and login processes, including social login options.
- **User Dashboard**: A personalized dashboard for managing messages and user settings.
- **Public Profiles**: Users can create public profiles to receive anonymous messages.
- **Real-time Notifications**: Users receive instant notifications for new messages.
- **Privacy Controls**: Users can manage who can send them messages and customize their experience.

## Technology Stack

### Frontend

- **Framework**: React.js with TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Routing**: React Router
- **Animations**: Framer Motion, React Spring

### Backend

- **Runtime**: Node.js with Express.js
- **Database**: PostgreSQL with Prisma ORM
- **Authentication**: JWT
- **Real-time Communication**: Socket.io

## Project Structure

```
anymmes-platform
├── backend
│   ├── src
│   ├── prisma
│   ├── tests
│   ├── package.json
│   ├── tsconfig.json
│   └── README.md
├── frontend
│   ├── public
│   ├── src
│   ├── tests
│   ├── tailwind.config.js
│   ├── package.json
│   ├── tsconfig.json
│   └── README.md
├── .env.example
├── docker-compose.yml
└── README.md
```

## Getting Started

### Prerequisites

- Node.js
- PostgreSQL
- Docker (optional)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/anymmes-platform.git
   cd anymmes-platform
   ```

2. Set up the backend:
   - Navigate to the `backend` directory.
   - Install dependencies:
     ```
     npm install
     ```
   - Set up the database and run migrations using Prisma.

3. Set up the frontend:
   - Navigate to the `frontend` directory.
   - Install dependencies:
     ```
     npm install
     ```

4. Run the application:
   - Start the backend server:
     ```
     npm run start
     ```
   - Start the frontend application:
     ```
     npm run start
     ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
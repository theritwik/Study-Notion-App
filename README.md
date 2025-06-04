# Study Notion App

A modern and responsive educational platform built with React that allows users to access learning resources with a secure authentication system.

## Features

- 🔐 User Authentication (Login/Signup)
- 🎯 Role-based Access (Student/Instructor)
- 🎨 Modern UI with Tailwind CSS
- 📱 Fully Responsive Design
- 🔄 Protected Routes
- 🌐 Google Authentication Integration
- 🔔 Toast Notifications

## Tech Stack

- **Frontend Framework:** React
- **Routing:** React Router v6
- **Styling:** Tailwind CSS
- **Icons:** React Icons
- **Notifications:** React Hot Toast
- **Authentication:** Custom implementation

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/study-notion-app.git
```

2. Navigate to the project directory
```bash
cd study-notion-app
```

3. Install dependencies
```bash
npm install
```

4. Start the development server
```bash
npm start
```

The application will be available at `http://localhost:3000`

## Project Structure

```
study-notion-app/
├── public/
├── src/
│   ├── assets/          # Images and static assets
│   ├── components/      # Reusable components
│   ├── pages/          # Page components
│   ├── App.js          # Main component
│   └── index.js        # Entry point
├── package.json
└── tailwind.config.js
```

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App

## Components

### Core Components

- **Navbar**: Navigation component with dynamic rendering based on authentication status
- **LoginForm**: Handles user login with email/password
- **SignupForm**: User registration with role selection
- **PrivateRoute**: Protected route wrapper for authenticated users
- **Template**: Reusable layout component for auth pages

### Pages

- **Home**: Landing page
- **Login**: User login page
- **Signup**: User registration page
- **Dashboard**: Protected user dashboard

## Styling

The project uses Tailwind CSS for styling with a custom configuration that includes:

- Custom color palette
- Custom font family (Inter)
- Responsive design utilities

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- React Team for the amazing framework
- Tailwind CSS for the utility-first CSS framework
- React Icons for the comprehensive icon library
- React Hot Toast for the toast notifications


# App Store

A full-stack web application that allows users to browse, search, and purchase apps. Users can also upload their own apps to the store.

## Features

- User Authentication
  - Login/Signup functionality
  - Token-based authentication
  - Secure password handling

- App Management
  - Browse available apps
  - Search apps by title and description
  - Upload new apps with images
  - Set pricing for apps

- Shopping Experience
  - View app details with images
  - Price display
  - Secure checkout process
  - Order confirmation

## Technologies Used

- Frontend:
  - React.js
  - Ant Design (antd) for UI components
  - React Hooks for state management
  - CSS for styling

- Backend Integration:
  - RESTful API integration
  - JWT authentication
  - Form data handling
  - File upload support

## Getting Started

1. Clone the repository:
```bash
git clone [your-repository-url]
```
2. Install dependencies:
```bash
npm install
```
3. Start the development server:
```bash
npm start
```
The application will open in your default browser at http://localhost:3000

## Environment Setup
Make sure you have the following installed:

Node.js (version 12 or higher)
npm (Node Package Manager)

## Project Structure
```bash
src/
├── components/
│   ├── HomePage.js
│   ├── LoginForm.js
│   ├── PostApps.js
│   └── SignupButton.js
├── utils.js
├── App.js
└── index.js
```

## API Integration
The application integrates with a backend API hosted at folkloric-air-420802.ue.r.appspot.com with the following endpoints:

/signin - User authentication
/signup - User registration
/upload - App upload
/search - App search
/checkout - Purchase processing

## Contributing 


1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

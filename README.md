# Social Media Feed Web Application

## Technology Stack
- Vite
- React + TypeScript
- Firebase (Authentication, Firestore, Storage)
- Tailwind CSS
- React Router

## Project Overview
A modern social media feed web application with features like infinite scrolling, multi-image posts, and real-time interactions.

## Prerequisites
- Node.js (v18+ recommended)
- npm or yarn
- Firebase Account

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/social-media-feed.git
cd social-media-feed
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Firebase Configuration
1. Create a Firebase project at https://console.firebase.google.com/
2. Enable the following services:
   - Authentication (Email/Password, Google Sign-In)
   - Firestore Database
   - Storage

3. Create a `.env` file in the project root with your Firebase configuration:
```
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### 4. Run the Application
```bash
# Development mode
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Available Scripts
- `dev`: Start development server
- `build`: Create production build
- `preview`: Preview production build
- `test`: Run tests
- `lint`: Run ESLint

## Project Structure
- `src/components/`: Reusable React components
- `src/context/`: React context providers
- `src/hooks/`: Custom React hooks
- `src/services/`: Firebase and API services
- `src/utils/`: Utility functions
- `src/styles/`: Global and Tailwind CSS
- `src/@types/`: TypeScript type definitions

## Features
- User Authentication
- Infinite Scrolling Feed
- Multi-Image/Video Posts
- User Profiles
- Real-time Interactions

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License.
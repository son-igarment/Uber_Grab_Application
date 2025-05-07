# Ride-Sharing Application

## Developed by Phạm Lê Ngọc Sơn

This application is an intuitive mobile platform that connects users to a wide range of on-demand services, including transportation, food delivery, and package delivery. It aims to simplify urban mobility and daily needs through a seamless user experience and cutting-edge technology.

## Project Structure

```
.
├── app/                      # Main application screens
│   ├── (api)/                # API routes
│   ├── (auth)/               # Authentication screens
│   │   ├── sign-in.tsx       # Sign in screen
│   │   ├── sign-up.tsx       # Sign up screen
│   │   └── welcome.tsx       # Welcome screen
│   └── (root)/               # Main application screens
│       ├── (tabs)/           # Tab navigation screens
│       │   ├── chat.tsx      # Chat screen
│       │   ├── home.tsx      # Home screen
│       │   ├── profile.tsx   # Profile screen
│       │   └── rides.tsx     # Rides history screen
│       ├── book-ride.tsx     # Book ride screen
│       └── find-ride.tsx     # Find ride screen
├── assets/                   # Images, fonts and other static assets
├── components/               # Reusable components
├── constants/                # Constants like colors, sizes, etc.
├── lib/                      # Utility functions
├── store/                    # State management with Zustand
└── types/                    # TypeScript type definitions
```

## Features

- **User Authentication**: Secure sign-up and sign-in functionality using Clerk
- **Location Services**: Real-time location tracking and destination search
- **Ride Booking**: Simple interface to book rides
- **Ride History**: View past rides and frequently visited locations
- **Profile Management**: Update user information and preferences
- **Chat Support**: In-app messaging for customer support

## Technologies Used

- React Native / Expo
- TypeScript
- Clerk for authentication
- Expo Router for navigation
- NativeWind (Tailwind CSS for React Native)
- Expo Location for geolocation services
- React Native Maps for map integration
- Zustand for state management

## Installation and Setup

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm start
   ```
4. Use Expo Go app on your mobile device to scan the QR code or run on an emulator

## Usage

1. Register a new account or sign in to your existing account
2. Allow location permissions when prompted
3. Enter your destination in the search bar
4. Select your ride type and proceed to booking
5. Track your ride in real-time once confirmed

## Project Credits

Designed and developed by Phạm Lê Ngọc Sơn

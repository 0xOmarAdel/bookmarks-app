# Bookmarks Web App

This is a web application built using React, React Router, TypeScript, and Tailwind CSS. It utilizes Firebase Firestore as the database.

## Features

- **Bookmarks Page**: Allows users to add bookmarks by selecting a category and providing the title and URL.

- **Profile Page**: Enables users to modify their account information, including first name, last name, email, and password.

- **Authentication**: Provides sign-up, log-in, and forgot password functionality.

## Technologies Used

- React
- React Router
- TypeScript
- Tailwind CSS
- Firebase Firestore

## Prerequisites

- Node.js and npm should be installed on your machine.

## Installation

1. Clone the repository: `git clone https://github.com/0xOmarAdel/bookmarks-app.git`
2. Navigate to the project directory: `cd bookmarks-app`
3. Install dependencies: `npm install`

## Configuration

To use Firebase Firestore as the database, you need to set up your Firebase project and obtain the configuration details. Add the configuration details to the `src/api/firebase.tsx` file. Then create a .env file in the project root directory and add the following line:
`VITE_API_KEY=your_api_key_here`

## Usage

Run the following command to start the development server:
`npm run dev`
Open your browser and visit `http://localhost:3000` to access the app.

To access the deployed version of the app, visit [Bookmarks App](https://bookmarks-react-firebase.netlify.app).

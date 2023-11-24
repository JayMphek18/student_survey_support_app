# Deployment Guide

## Student Survey and Support App

This guide provides step-by-step instructions for deploying the Student Survey and Support App using Docker for the backend and React Native for the frontend.

### Prerequisites

Before you begin, ensure that you have the following prerequisites installed on your system:

1. **Docker:**
   - [Install Docker](https://docs.docker.com/get-docker/)

2. **Node.js and npm:**
   - [Install Node.js and npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

3. **React Native CLI:**
   - Install the React Native CLI globally by running:
     ```bash
     npm install -g react-native-cli
     ```

### Backend Deployment (Docker)

1. **Clone the Repository:**
   ```bash
   git clone [repository-url]
   cd backend
   ```

2. **Build Docker Image:**
   ```bash
   docker build -t student-survey-backend .
   ```

3. **Run Docker Container:**
   ```bash
   docker run -p 5000:5000 student-survey-backend
   ```

### Frontend Deployment (React Native)

1. **Navigate to the Frontend Directory:**
   ```bash
   cd frontend
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Run the App:**
   - For Android:
     ```bash
     react-native run-android
     ```
   - For iOS:
     ```bash
     react-native run-ios
     ```

### Access the App

Once both backend and frontend are deployed, you can access the app through your browser or the React Native app on your emulator or physical device.

- Backend: [http://localhost:5000](http://localhost:5000)
- Frontend: Follow the instructions on your React Native development environment to run the app on an emulator or physical device.

### Troubleshooting

If you encounter any issues during deployment, refer to the respective documentation for Docker and React Native. Additionally, check for error messages in the terminal to diagnose and resolve any problems.

For further assistance, contact our development team at [contact@example.com](mailto:contact@example.com).

Thank you for deploying the Student Survey and Support App!

# Assignment-10

This repository contains a chat application built with React and Node.js.

## Project Structure

- **my-chat-backend/**: Contains the backend code for the chat application.
- **public/**: Public assets for the frontend.
- **src/**: Source code for the React frontend.

## Available Scripts

Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified, and the filenames include hashes. Your app is ready to be deployed!

## Backend Setup

Navigate to the `my-chat-backend` directory:

```bash
cd my-chat-backend
```

Install the backend dependencies:

```bash
npm install
```

Start the backend server with strapi:

```bash
npm run develop
```

Ensure the backend server is running before starting the frontend.

## Frontend Setup

Navigate back to the root directory and install frontend dependencies:

```bash
npm install
```

Start the frontend application:

```bash
npm start
```

## Deployment

To deploy the frontend application, run:

```bash
npm run build
```

This will create a `build` folder with the production build of your app. You can then deploy this folder to your preferred hosting platform.

## Learn More

To learn more about React and Create React App, check out the [React documentation](https://reactjs.org/) and the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

---

*Note: This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).*

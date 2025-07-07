# **DOCVIEW: AI Document Analyzer**

Welcome to **DocView**! This is a full-stack **(MERN-Stack)** application that integrates an AI-powered document processing backend with a React-based frontend. The app allows users to upload documents for summarization, generate key insights, and chat with an AI based on the document's content.

<h2 id="-overview">📖 Overview</h2>

The **DocView** app is designed to provide users with a simple, AI-powered document management tool. Users can upload PDFs or Word documents and receive summaries, key insights, and discussion points. Additionally, users can chat with an AI using the document's content for further clarification.

**DocView** is created using the **MERN-Stack** architecture, which stands for **Firebase, Express, React, and Node.js**. The backend is built with Node.js and Express, integrating Firebase for user authentication and MongoDB for data storage. The frontend is built with React and Material-UI, providing a responsive and user-friendly interface.

> [!IMPORTANT]
> It is currently deployed live on **Vercel** and **Render**. You can access the live app **[here](https://DocView-fullstack-app.vercel.app/)**.

<h2 id="live-deployments">🚀 Live Deployments</h2>

> [!TIP]
> Access the live app at **[https://DocView.vercel.app/](https://DocView.vercel.app/) by clicking on the link or copying it into your browser! 🚀**

We have deployed the entire app on **Vercel** and **Render**. You can access the live app **[here](https://DocView.vercel.app)**.

- **Frontend**: Deployed on **Vercel**. Access the live frontend **[here](https://DocView.vercel.app/)**.
  - **Backup Frontend**: We have a backup of the frontend on **Netlify**. You can access the backup app **[here](https://DocView-ai-app.netlify.app/)**.
- **Backend**: Deployed on **Vercel**. You can access the live backend **[here](https://DocView-app-backend-api.vercel.app/)**.
  - **Backup Backend API**: Deployed on **Render**. You can access the backup backend **[here](https://DocView-ai-app.onrender.com/)**.

> [!IMPORTANT]
> The backend server may take a few seconds to wake up if it has been inactive for a while. The first API call may take a bit longer to respond. Subsequent calls should be faster as the server warms up.

> [!NOTE]
> Additionally, the Render-deployed backend is currently on the **Free Tier** of **Render**, so it may take longer to process your request since we are only allocated **512MB and 0.1 CPU**.

<h2 id="features">✨ Features</h2>

**DocView** offers a wide range of features to help users manage and analyze their documents effectively. Here are some of the key features of the app:

- **Document Upload & Summarization**: Upload PDFs or Word documents for AI-generated summaries.
- **Key Insights & Discussion Points**: Generate important ideas and topics for discussion from your documents.
- **AI Chat Integration**: Chat with an AI using your document’s original context.
- **Voice Chat with AI**: Chat with an AI using voice commands for a more interactive experience.
- **Sentiment Analysis**: Analyze the sentiment of your document text for emotional insights.
- **Multiple Language Support**: Summarize documents in different languages for global users.
- **Content Rewriting**: Rewrite or rephrase document text based on a specific style or tone.
- **Actionable Recommendations**: Get actionable recommendations based on your document content.
- **Bullet Point Summaries**: Generate bullet point summaries for quick insights and understanding.
- **Document Categorization**: Categorize documents based on their content for easy organization.
- **Profile Management**: Update your profile information, social media links, and theme settings.
- **User Authentication**: Secure registration, login, and password reset functionality.
- **Document History**: View all uploaded documents and their details.
- **Mobile App Integration**: React Native mobile app for on-the-go document management.
- **API Documentation**: Swagger (OpenAPI) documentation for all API endpoints.
- **Authentication Middleware**: Secure routes with JWT and Firebase authentication middleware.
- **Containerization**: Dockerized the app with Docker & K8s for easy deployment and scaling.
- **Continuous Integration**: Automated testing and deployment with GitHub Actions & Jenkins.

<h2 id="technologies">⚙️ Technologies</h2>

- **Frontend**:
  - **React**: JavaScript library for building user interfaces.
  - **Material-UI**: React components for faster and easier web development.
  - **Axios**: Promise-based HTTP client for making API requests.
  - **React Router**: Declarative routing for React applications.
  - **Context API**: State management for React applications.
  - **TailwindCSS**: Utility-first CSS framework for styling.
  - **Craco**: Create React App Configuration Override for customizing Webpack.
  - **Webpack**: Module bundler for JavaScript applications.
  - **Jest**: JavaScript testing framework for unit and integration tests.
  - **React Testing Library**: Testing utilities for React components.
- **Backend**:
  - **Express**: Web application framework for Node.js.
  - **Redis**: In-memory data structure store for caching.
  - **Firebase Admin SDK**: Firebase services for server-side applications.
  - **Node.js**: JavaScript runtime for building scalable network applications.
  - **Firebase Authentication**: Secure user authentication with Firebase.
  - **Firebase Auth JWT**: Generate custom tokens for Firebase authentication.
  - **Middlewares**: Firebase authentication middleware for securing routes and JWT middleware for token verification.
  - **REST APIs**: Representational State Transfer for building APIs.
  - **GraphQL**: Query language for APIs and runtime for executing queries.
  - **RabbitMQ**: Message broker for handling asynchronous tasks and background jobs.
  - **Swagger/OpenAPI**: API documentation for all endpoints.
- **AI/ML Services**:
  - **Google Cloud Natural Language API**: Machine learning models for text analysis.
  - **Google Speech-to-Text API**: Speech recognition for voice chat integration & text extraction from audio.
  - **Google AI Studio**: Tools for building and deploying machine learning models.
  - **NLP**: Natural Language Processing for customized chat/text analysis and summarization models.
  - **NER**: Named Entity Recognition for identifying entities in text.
  - **POS Tagging**: Part-of-Speech Tagging for analyzing word types in text.
  - **RAG**: Retrieval-Augmented Generation for generating responses in chat.
  - **LangChain**: Handles document ingestion, text chunking, embedding storage, retrieval, summarization, and API chaining for generating insights from uploaded documents.
- **Database**:
  - **MongoDB**: NoSQL database for storing user data and documents.
  - **Firestore**: Cloud Firestore for storing user data and documents.
  - **Redis**: In-memory data structure store for caching.
- **Mobile App**:
  - **React Native**: JavaScript framework for building mobile applications.
  - **Expo**: Framework and platform for universal React applications.
  - **Firebase SDK**: Firebase services for mobile applications.
  - **React Navigation**: Routing and navigation for React Native apps.
- **API Documentation**:
  - **Swagger**: OpenAPI documentation for all API endpoints.
  - **OpenAPI**: Specification for building APIs with RESTful architecture.
- **Containerization**:
  - **Docker**: Containerization platform for building, shipping, and running applications.
  - **Kubernetes**: Container orchestration for automating deployment, scaling, and management.
- **Load Balancing & Caching**:
  - **NGINX**: Web server for load balancing, reverse proxying, and caching.
- **CI/CD & Deployment**:
  - **GitHub Actions**: Automated workflows for testing and deployment.
  - **Jenkins**: Automation server for continuous integration and deployment.
  - **Render**: Cloud platform for hosting and scaling web applications. (Used to deploy the backend)
  - **Vercel**: Cloud platform for hosting and deploying web applications. (Used to deploy the frontend)
  - **Netlify**: Cloud platform for hosting and deploying web applications. (Used as a backup)
- _and more!_

<h2 id="getting-started">🛠️ Getting Started</h2>

### **Prerequisites**

Ensure you have the following tools installed:

- **Node.js** (between v14 and v20)
- **npm** or **yarn**
- **Firebase Admin SDK** credentials
- **Redis** for caching
- **MongoDB** for data storage
- **RabbitMQ** for handling asynchronous tasks
- **Docker** for containerization (optional)
- **Postman** for API testing (optional)
- **Expo CLI** for running the mobile app
- **Jenkins** for CI/CD (optional)
- **Kubernetes** for container orchestration (optional)
- **React Native CLI** for building the mobile app
- **Firebase SDK** for mobile app integration
- **Firebase API Keys and Secrets** for authentication
- **Expo Go** app for testing the mobile app on a physical device
- **Tailwind CSS** for styling the frontend
- **.env** file with necessary API keys (You can contact me to get the `.env` file - but you should obtain your own API keys for production).

Additionally, **basic fullstack development knowledge and AI/ML concepts** are recommended to understand the app's architecture and functionalities.

### **Frontend Installation**

1. **Clone the repository**:

   ```bash
   git clone https://github.com/hoangsonww/DocView-AI-App.git
   cd DocView-AI-App/backend
   ```

2. **Navigate to the frontend directory**:

   ```bash
   cd frontend
   ```

3. **Install dependencies**:

   ```bash
   npm install
   ```

   Or `npm install --legacy-peer-deps` if you face any peer dependency issues.

4. **Start the Frontend React app**:
   ```bash
   npm start
   ```
5. **Build the Frontend React app (for production)**:

   ```bash
   npm run build
   ```

6. **Alternatively, you can use `yarn` to install dependencies and run the app**:
   ```bash
   yarn install
   yarn start
   ```
7. **Or, for your convenience, if you have already installed the dependencies, you can directly run the app in the root directory using**:

   ```bash
   npm run frontend
   ```

   This way, you don't have to navigate to the `frontend` directory every time you want to run the app.

8. **The app's frontend will run on `http://localhost:3000`**. You can now access it in your browser.

### **Backend Installation**

> [!NOTE]
> Note that this is optional since we are deploying the backend on **Render**. However, you can (and should) run the backend locally for development purposes.

1. **Navigate to the root (not `backend`) directory**:
   ```bash
   cd backend
   ```
   
2. **Install dependencies**:
   ```bash
   npm install
   ```

   Or `npm install --legacy-peer-deps` if you face any peer dependency issues.

3. **Start the backend server**:
   ```bash
   npm run server
   ```
   
4. **The backend server will run on `http://localhost:3000`**. You can access the API endpoints in your browser or **Postman**.
5. **Additionally, the backend code is in the `backend` directory**. Feel free to explore the API endpoints and controllers.

> [!CAUTION]
> **Note:** Be sure to use Node v.20 or earlier to avoid compatibility issues with Firebase Admin SDK.

### **Running the Mobile App**

1. **Navigate to the mobile app directory**:
   ```bash
   cd mobile-app
   ```
2. **Install dependencies**:
   ```bash
    npm install
   ```
3. **Start the Expo server**:
   ```bash
   npx expo start
   ```
4. **Run the app on an emulator or physical device**: Follow the instructions in the terminal to run the app on an emulator or physical device.

<h2 id="deployment">🚧 Deployment</h2>

### **Frontend Deployment (Vercel)**

1. **Install the Vercel CLI**:

   ```bash
   npm install -g vercel
   ```

2. **Deploy the frontend**:

   ```bash
   vercel
   ```

3. **Follow the instructions in your terminal to complete the deployment**.

### **Backend Deployment (Render)**

- The backend can be deployed on platforms like **Heroku**, **Render**, or **Vercel**.

- Currently, we are using **Render** to host the backend. You can access the live backend **[here](https://DocView-ai-app.onrender.com/)**.

### **Important Note about Backend Deployment**

> [!IMPORTANT]
> - Please note that we are currently on the **Free Tier** of **Render**. This means that the backend server may take a few seconds to wake up if it has been inactive for a while.
>
> - Therefore, the first API call may take a bit longer to respond. Subsequent calls should be faster as the server warms up. It is completely normal to take up to 2 minutes for the first API call to respond.
>
> - Also, the **Free Tier** of **Render** only allocates **512MB and 0.1 CPU**. This may result in slower response times for API calls and document processing.
>
> - Additionally, during high traffic periods, the server may take longer to respond, although we have employed [NGINX](#load-balancing) for load balancing and caching.

### ⭐ If you like this project, please consider giving it a star on [GitHub](https://github.com/pratikabhang/CREDBUD--The-Student-Platform)! It helps a lot! ⭐
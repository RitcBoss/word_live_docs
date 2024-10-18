
# Live Document Project

readme_content_tshirt_with_link = "https://word-live-docs.vercel.app/"

## Description
This project was created to help improve programming skills and explore new technologies. It focuses on building a live document editor where multiple users can collaborate in real-time. You can follow the original tutorial on [YouTube](https://www.youtube.com/@javascriptmastery).

## Features
The application offers the following key features:
- **Google Login**: Users can sign in to the application using their Gmail account through Google authentication.
- **Document Management**: Users can create new documents and delete existing ones.
- **Real-time Collaboration**: Users can share documents with others, allowing them to edit the document simultaneously. The document owner has the ability to assign permissions (viewer or editor) to other users.
- **Live Editing**: All users can see real-time changes made to the document, with updates happening instantly for everyone.
- **Notifications**: Users receive notifications when someone makes changes to their shared documents.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   First, clone the project from GitHub:
   ```bash
   git clone <your-repository-url>
   cd live-document
   ```

2. **Install Dependencies**:
   Run the following command to install all the required packages:
   ```bash
   npm install
   ```

3. **Start the Development Server**:
   After installing the dependencies, you can start the development server using:
   ```bash
   npm run dev
   ```

4. **Access the Application**:
   Open your browser and go to `http://localhost:3000` to use the live document editor.

## Technologies Used
- **Next.js**: A React framework for building web applications.
- **TypeScript**: For static type checking to make the code more reliable.
- **Tailwind CSS**: For efficient and easy styling.
- **Liveblocks**: To enable real-time collaboration and live document updates.
- **Clerk**: For managing authentication, including Google login.
- **Sentry**: To track and monitor errors during development and in production.

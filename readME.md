TaskMaster
TaskMaster is a comprehensive task management web application that allows users to create, manage, and track their tasks efficiently. This project includes user authentication, a personalized dashboard, and task management features.

Features
User registration and login
Secure authentication system
Personalized user dashboard
Task creation, editing, and deletion
Task filtering and sorting
Archived tasks view
Dark mode toggle
Mobile-responsive design
File Structure
This file structure accurately represents all the main files we've created for the TaskMaster project, including:

frontend/: Contains all client-side files

HTML files (*.html): Define the structure of each page
CSS files (*.css): Style the HTML elements
JavaScript files (*.js): Provide client-side functionality
backend/: Contains server-side files

server.js: The main Node.js server file that handles API requests, authentication, and serves the application
schema.js: Defines the database schema for users and tasks
README.md: Provides an overview and documentation for the project

Setup Instructions
Clone the repository: https://github.com/thebabalola/3mtt-SE_Capstone_Project.git

Open the project in your preferred code editor.

If you're using a local development server, start it in the project root directory.

Open your browser and navigate to http://localhost:8000 (or whatever port your local server is using).

Usage
Landing Page:
Open index.html in your browser to view the landing page.
Click on "Login" or "Register" to navigate to the respective pages.
Registration:
Fill out the registration form with your details.
Click "Register" to create a new account.
Login:
Enter your email and password.
Click "Login" to access your dashboard.
Dashboard:
View your profile information, including your join date.
See statistics about your created and archived tasks.
Manage your active tasks.
View your archived tasks.
Toggle dark mode using the settings panel.
Logout:
Click the "Logout" button in the navigation bar to log out and return to the landing page.
Customization
To change the color scheme, modify the CSS variables in the :root selector in thestyles.css
To add or modify features, edit the respective HTML, CSS, and JavaScript files.
Backend Integration
This project currently uses mock data and simulated API calls. To integrate with a real backend:

Replace the simulated API calls in auth.js and dashboard.js with actual AJAX requests to your backend server.
Implement proper error handling for API responses.
Ensure your backend provides endpoints for user authentication, task management, and user profile operations.#   c a p s t o n - p r o j e c t  
 #   c a p s t o n - p r o j e c t  
 
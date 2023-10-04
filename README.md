# Contact Keeper
Contact Keeper is a feature-rich contact management application built with React and Express. It provides users with the ability to register, log in, add, edit, and delete contacts, making it a valuable tool for organizing and managing contact information.

## Frontend
The frontend of this application is built using React and employs the Context API for efficient state management. Key components include:

- **Register.js** and **Login.js**: These components handle user registration and login processes.
- **ContactForm.js**: Allows users to seamlessly add or edit contacts.
- **ContactItem.js**: Renders individual contact items.
- **Contacts.js**: Displays a comprehensive list of contacts.
- **Alerts.js**: Provides a user-friendly way to view alerts from the alert context.
- **Home.js**: Serves as the main page component for authenticated users.
- **App.js**: This primary component sets up the application, manages routing, and facilitates global state management.

## Backend
The backend of the application is constructed using Express and is responsible for interacting with a MongoDB database. Key files include:

- **users.js**: Defines routes for user registration.
- **auth.js**: Manages routes related to authentication.
- **server.js**: Serves as the entry point for the Express server.
- **db.js**: Establishes the connection to the MongoDB database.

## Context Providers
- **AuthState.js**: Offers global state management for authentication-related functionalities.
- **ContactState.js**: Manages contact data and state globally.

## Utility
- **setAuthToken.js**: Handles the management of authentication tokens for axios requests.

## Installation
To set up the project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run ```npm install``` to install all the required dependencies.
4. Start the application with ```npm start```.

## Contributing
Contributions to this project are encouraged and welcomed. If you plan to submit a pull request, please ensure that you update and include appropriate tests before doing so.

## License
This project is licensed under the MIT License.

Feel free to customize and use this Contact Keeper application to efficiently manage your contacts. If you have any questions or require further assistance, please don't hesitate to reach out. Happy contact management! 📇✨

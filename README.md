# Secrets App

This project is a simple web application that fetches and displays random secrets from an external API. It demonstrates the use of server-side rendering with EJS, handling HTTP requests with Express, and making API calls using Axios.

![Project Screenshot](public/images/secrets-app.png)

## Features
- Fetches random secrets from an external API.
- Displays the secret along with the associated username.
- Simple and responsive design for desktop and mobile devices.

## Technologies Used
- **Node.js**: JavaScript runtime for server-side development.
- **Express.js**: Web framework for handling HTTP requests and routing.
- **EJS (Embedded JavaScript Templates)**: For dynamic server-side rendering.
- **Axios**: For making HTTP requests to external APIs.
- **CSS**: For basic styling and layout.

## How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ammarjw/secrets-app.git
   cd secrets-app
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the app:**

   Using Nodemon for auto-reload on code changes:
   ```bash
   nodemon index.js
   ```
   Or simply:
   ```bash
   node index.js
   ```

   ### Quick Tip
   If Nodemon isn't installed:
   ```bash
   npm install -g nodemon
   ```

4. **Open the app:**  
   Visit `http://localhost:3000` in your browser to see the app in action.

## Notes
- The app fetches random secrets from [Secrets API](https://secrets-api.appbrewery.com).
- Ensure you have an active internet connection to retrieve secrets from the API.
- This project focuses on API integration and dynamic content rendering.


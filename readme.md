🛡️ Women Safety Application

  A robust web application built with the MERN (subset) stack designed to provide quick access to safety tools and
  emergency resources. This project focuses on user authentication, guardian management, and emergency alerts.

  🚀 Features

   - User Authentication: Secure Sign Up and Login using Passport.js and JWT.
   - Guardian Management: Add and manage trusted contacts (Guardians).
   - Emergency Tools:
       - SOS Alarm: Integrated siren system for immediate alerts.
       - Navigation: Quick access to safety-related locations.
   - Session Management: Secure sessions with MongoDB-backed storage.
   - Real-time UI: Responsive design using EJS templates and custom CSS.

  🛠️ Tech Stack

   - Backend: Node.js, Express.js
   - Database: MongoDB (via Mongoose)
   - Authentication: Passport.js (Local Strategy)
   - Templating: EJS (Embedded JavaScript)
   - Styling: Vanilla CSS

  📋 Prerequisites

  Before running the project, ensure you have:
   - Node.js (https://nodejs.org/) installed (v14+ recommended)
   - MongoDB (https://www.mongodb.com/) installed and running locally, or a MongoDB Atlas URI.

  ⚙️ Installation & Setup

   1. Clone the repository:

   1    git clone https://github.com/Satyajeetgonugade/Women-Safety-Webapplication-Guardia
   2    cd "Women Safety (1)/Women_Safety"

   2. Install Dependencies:
   1    npm install

   3. Environment Configuration:
     Create a .env file in the Women_Safety directory and add your configuration:

   1    # Example .env content
   2    SESSION_SECRET=your_secret_key_here (use this key: skdgngknasdaf)
	
   
  🏃 Running the Application

  To start the server in development mode with Nodemon (which auto-restarts on changes), use:

   1 npm run dev

  The server will typically start on http://localhost:3000 (check your index.js for the exact port).

  📂 Project Structure

   1 Women_Safety/
   2 ├── controller/     # Business logic for Users and Guardians
   3 ├── model/          # Mongoose schemas (User, Guardian)
   4 ├── public/         # Static assets (CSS, JS, Images, Audio)
   5 ├── views/          # EJS templates for the UI
   6 ├── index.js        # Main entry point
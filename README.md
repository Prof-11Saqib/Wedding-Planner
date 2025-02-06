WeddingWizard

What is WeddingWizard?

WeddingWizard is a website that helps make wedding planning easier. It helps with organizing all the important details, so everything runs smoothly. The website is built using modern tools like TypeScript, Express.js, Vite, and Tailwind CSS, making it fast, reliable, and easy to use.

Features

User-Friendly Design: The website is made using Vite and Tailwind CSS, so it looks good and works well on all devices.

Powerful Backend: Express.js handles all the important functions, like managing data and making sure everything runs smoothly.

Smart Database System: Drizzle ORM helps store and organize information so that it is always easy to find and use.

Media Storage: The website can handle pictures, videos, and other media files efficiently.

Project Structure

WeddingWizard/
├── client/                 # Frontend (What users see)
│   ├── src/
│   │   ├── index.html      # Main webpage file
├── node_modules/           # Project dependencies
├── server/                 # Backend (How the website works)
│   ├── index.ts            # Main server file
│   ├── routes.ts           # Controls different pages and features
│   ├── storage.ts          # Handles media files
│   ├── vite.ts             # Configures Vite
├── shared/                 # Shared resources
│   ├── schema.ts           # Database structure
├── .gitignore              # Files to ignore in Git
├── package.json            # Project settings and dependencies
├── postcss.config.js       # Configures styling options
├── tailwind.config.ts      # Tailwind CSS settings
├── theme.json              # Website theme settings
├── tsconfig.json           # TypeScript settings
├── vite.config.ts          # Vite settings

How to Install and Run

Things You Need First

Node.js (Download from nodejs.org)

npm (Comes with Node.js)

Steps to Start the Project

Download the project:

git clone https://github.com/Prof-11Saqib/Wedding-Planner.git
cd Wedding-Planner

Install everything needed:

npm install

Start the development server:

npm run dev

The website backend will run at http://localhost:5000.

How to Put It Online

To make WeddingWizard available for others, use services like:

Vercel or Netlify (for hosting the frontend)

Render or Heroku (for hosting the backend)

Who Worked on This?

This project is divided into four main parts:

Frontend Development – Designs the website's appearance and features.

Backend Development – Handles how the website works behind the scenes.

Database & Storage – Manages and stores data securely.

Deployment & Configuration – Makes sure the project runs well online.

License

This project follows the MIT License. Check the LICENSE file for details.

Need Help?

If you have questions, syedsaquibmustafa23.com or create an issue in the project repository.


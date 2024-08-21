# Ticket-ok: Your Simple Ticketing System

Ticket-ok is a simple ticketing system built using JavaScript. It allows users to create, view, and manage tickets within their projects. This readme file will guide you on how to set up and run the project on your local machine.

## Prerequisites
Before running Ticket-ok, make sure you have the following installed:
- Node.js (v14 or higher)
- npm (comes with Node.js)
- Git

## Clone the Repository
```bash
git clone https://github.com/yourusername/ticket-ok.git
cd ticket-ok
```

## Install Dependencies
```bash
npm run installAll
```

## Start the Server & the client
To start the development server & Client, i two different terminals run these two commands 

Server :
```bash
npm run back
```

Client : 
```bash
npm run front
```

This will start a local development server & client. Open your web browser and visit `http://localhost:5174/` to see the Ticket-ok in action.

## Build for Production (tbd)
To build the project for production, run:
```bash
npm run build
```

This will create a production-ready version of the application in the `dist` folder. You can deploy this folder to any web server or hosting service to make your Ticket-ok system available online.


## License
This project is licensed under the [MIT License](LICENSE).

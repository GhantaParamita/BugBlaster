# Bug Blaster

**Live Demo:** [https://GhantaParamita.github.io/BugBlaster](https://GhantaParamita.github.io/BugBlaster)

## Overview

Bug Blaster is a React-based ticket management application designed to help teams track, manage, and prioritize bug reports and tasks. Users can create new tickets, assign priority levels, edit existing tickets, and sort them based on priority.

## Features

- **Create Tickets**: Add new bug reports or tasks with description and priority level
- **Manage Tickets**: Edit existing tickets or delete them
- **Priority Sorting**: Sort tickets by priority (High to Low or Low to High)
- **State Management**: Uses React's useReducer hook for efficient state management
- **Responsive UI**: Clean and intuitive user interface

## Technology Stack

- **React** 18.3.1
- **React DOM** 18.3.1
- **React Scripts** 5.0.1
- **CSS** for styling

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### `npm run deploy`

Deploys the application to GitHub Pages.

## Project Structure

```
src/
├── components/        # React components
│   ├── TicketForm.js     # Form component for creating/editing tickets
│   ├── TicketList.js     # Component to display list of tickets
│   └── TicketItem.js     # Individual ticket item component
├── reducers/          # State management
│   └── ticketReducer.js  # Reducer for ticket state
├── utilities/         # Helper functions
│   └── sortingUtilities.js # Ticket sorting logic
├── App.js            # Main application component
├── App.css           # App styles
└── index.js          # Application entry point
```

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the development server: `npm start`
4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deployment

This project is deployed to GitHub Pages. To deploy your changes:

```bash
npm run deploy
```

This will build the app and deploy it to the URL specified in the `homepage` field of package.json.

## Learn More

To learn more about React, check out the [React documentation](https://reactjs.org/).

For more information about Create React App, see the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

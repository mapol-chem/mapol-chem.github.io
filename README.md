### Prerequisites

node.js with npm

## Available Scripts

In the project directory, you can run:

### `npm install`
Installs required packages as specified in package.json

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run deploy`

Deploys the application using GitHub Pages to [https://mapol-chem.github.io](https://mapol-chem.github.io)

## Development with Docker

Start the Development Environment

`docker compose up --build`

-Build the frontend and backend images
-Start the containers with hot-reloading enabled


Rebuild Only One Service

`docker compose up --build frontend`


Stop the App

`docker compose down`

Access the App

Frontend: http://localhost:5173/
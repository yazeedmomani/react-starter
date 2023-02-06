# Before Getting Started

## Essential Packages

- ### gh-pages

    1.  Download using npm

            npm install gh-pages --save-dev

    2.  Add the below property to the _package.json_ file:

            {
                "homepage": "your-home-url",
            }

    3.  Add these scripts to the _package.json_ file in the _scripts_ object:

            {
                "predeploy": "npm run build",
                "deploy": "gh-pages -d build",
            }

- ### react-router

        npm install react-router-dom

- ### react-helmet

        npm install --save react-helmet

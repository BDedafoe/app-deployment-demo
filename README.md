Created simple App Deployment Demo for myself to troubleshoot issues I've had deploying existing react apps to Heroku.

This app had errors in the beginning but is now successfully launched.

DESPITE what online tutorials stated; the fix to my Heroku errors came from REMOVING the https://github.com/mars/create-react-app-buildpack that was stated to add to your Heroku buildpack. 

I only have heroku/nodejs as a buildpack for this app.

1. npx create-react-app app-deployment
2. added "engines" to package.json with npm and node versions
3. created a Git Repo for the app
4. logged into Heroku via URL and deployed the app via GitHub and not Heroku Git


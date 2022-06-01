# Sql Editor
This is an online SQL editor built specifically for the frontend task of Atlan's front-end engineering role. This particular project is built using React, and the React Bootstrap front-end framework. It originally contains a data dump borrowed from a graphql repository. The sections below contains salient features of this project.

# Features
Tab-Based Interface: An easy-to-use tab based interface allows the user to switch between multiple queries at once. It's possible to view a table and run a query at the same time. Each tab maintains a separate state, as long as you don't reload the page, you can jump right back to where you left a tab.
Dynamically Rendered Table Views: The list of tables is fetched at first, but the actual data isn't. When you click on the name of a table, then, the entries fetched. Keeping the application simple -lightweight, and fast.
Result Statistics: The user will also be alerted about the time taken to complete a query, giving the user a measure to check the performance of the system.
Ability to save the results as JSON, XML, or CSV: This application includes functionality to save the results of a query in JSON, XML, and CSV formats. 

# Performance Ratio
GTmetrix: The fully loaded time is 1.4 seconds, with the first contentful paint at 969 ms. The site receives an A grade too.
web.dev: The load time according to web.dev is 2.2 seconds. The site also scores 96 points in performance and 100 points in best practices. The exact metrics are:
First Contentful Paint: 2.2s
Speed Index: 2.2s
Largest Contentful Paint: 2.2s
Time to Interactive: 2.2s
Total Blocking Time: 0ms
Cumulative Layout Shift: 0
Chrome DevTools: The load time according to Chrome DevTools is 3.97 seconds. I got this load time from the load event in the Network tab of the DevTools. Along the same lines, the DOMContentLoaded event fires after 3.60 seconds.

# Available Scripts
In the project directory, you can run:

npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

npm build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

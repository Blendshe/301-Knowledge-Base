Getting Started with Create React App
This project was bootstrapped with Create React App.

Available Scripts
In the project directory, you can run:

npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

npm test
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.

npm run eject
Note: this is a one-way operation. Once you eject, you can't go back!

If you aren't satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except eject will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use eject. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.  

## Lab 01  

Overview
By the end of this module, you will create an application that displays images and information of horned animals. This application will allow you to filter the images by number of horns and chose your favorite image.

For this class we will just be focusing on the component structure of the application. You will create a new React application using create-react-app and fill it with components. Refer to 'Feature Tasks' to see exactly which components to build and where to display them.

Feature Tasks
Complete the following steps to setup your repository:

Create a React application using create-react-app as demonstrated in class.
Use the command npx create-react-app <repo-name>.
Create a new repository on GitHub WITHOUT a README.md. We will import an "existing" repository with its own README
Follow the instructions given by GitHub to "push an existing repository from the command line"
be sure to select HTTPS or SSH, whichever is relevant for you
Create a Branch and begin your work. As always, ACP often
Your App component should render a Header, Footer and Main component, each of which is defined in their own files.

Your Header component needs to have an <h1> with a title.

Your Footer component needs to contain your name as the author.

The Main component needs to render at least two copies of a component called HornedBeast.

The Main component needs to pass title, imageUrl, and description into each HornedBeast component. For the purpose of this lab, you can pass whatever title, url and description that you want into each HornedBeast component.

The HornedBeast component needs to contain an <h2> that displays the title of the animal, an <img> element with src, alt and title attributes, and a <p> that displays the description.

NOTE: Rendering an image in React is a little tricky. Try to figure out how to do this on your own and we will go over it in the next code review
Stretch Goal  
  
Given the following array, loop over the data to display three HornedBeast components:
  
```
[{
    "_id": 1,
    "image_url": "http://3.bp.blogspot.com/_DBYF1AdFaHw/TE-f0cDQ24I/AAAAAAAACZg/l-FdTZ6M7z8/s1600/Unicorn_and_Narwhal_by_dinglehopper.jpg",
    "title": "UniWhal",
    "description": "A unicorn and a narwhal nuzzling their horns",
    "keyword": "narwhal",
    "horns": 1
  },

  {
    "_id": 2,
    "image_url": "https://images.unsplash.com/photo-1512636618879-bbe79107e9e3?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=bd9460ee6d1ddbb6b1ca7be86dfc4590&auto=format&fit=crop&w=1825&q=80",
    "title": "Rhino Family",
    "description": "Parent rhino with two babies",
    "keyword": "rhino",
    "horns": 2
  },

  {
    "_id": 3,
    "image_url": "https://www.dhresource.com/0x0s/f2-albu-g5-M00-1A-11-rBVaI1hsIIiALxKzAAIHjSU3VkE490.jpg/wholesale-halloween-costume-prop-unicorn.jpg",
    "title": "Unicorn Head",
    "description": "Someone wearing a very silly unicorn head mask",
    "keyword": "unicorn",
    "horns": 1
}]
```
Submission Instructions
Complete your Feature Tasks for the day.
Create a Pull Request (PR) back to the main branch of your repository.
Submit your assignment as a link to your PR, and a comment describing how much time you spent on the lab.
Learn More
You can learn more in the Create React App documentation.

To learn React, check out the React documentation.

Code Splitting
This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

Analyzing the Bundle Size
This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

Making a Progressive Web App
This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

Advanced Configuration
This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

Deployment
This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

npm run build fails to minify
This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify

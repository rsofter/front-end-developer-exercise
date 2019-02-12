# Front-End Developer Exercise

## Instructions

You are building a list of event team members using React.js.

#### Details
- Use the JPG or Sketch file contained in this repository as your visual guide. If you'd like, you can download a trial of Sketch here: https://www.sketchapp.com/
- You must consume this endpoint (http://jsonplaceholder.typicode.com/users) to get the users for the list. How you consume the endpoint is up to you.
- You can use static CSS, setup a CSS precompiler + watching, or use inline styling
- You should be able to filter the list by typing into the filter text input
- Clicking on a row should expand it to reveal the user's address -- only one row should be able to be expanded at a time
- You should demonstrate knowledge on how to construct and re-use components

#### Bonus points
- Use ES6
- Write tests for your components
- Demonstrate knowledge of pure functions / components

#### For fun / if you want to get crazy
- Find a way to incorporate Redux (We use it heavily)
- Add animation to the expanding rows
- Output some location-relative information using the latitude / longitude returned by the API endpoint for each user
- Add a "loading" indicator for when the users are being fetched
- Use a Gravatar for displaying a user's avatar based on the user's email

#### To submit
- Send Alex (aleksandrm@xara.com) an email with a link to your repository

#### Notes
- The design shows just a sampling of users. You should display all of the users that the endpoint returns.
- For the icons, use FontAwesome (https://fortawesome.github.io/Font-Awesome/icons/). The CSS has already been included in the project.

#### Questions / problems / comments?
Contact Alex - aleksandrm@xara.com

---

## How to get up and running...

#### Step 1 - Install Webpack
```
> $ npm install webpack-dev-server webpack -g
```

#### Step 2 - Clone this repository and install modules
In the directory where you'd like this repository to live, run the following commands:

```
> $ git clone git@github.com:rsofter/front-end-developer-exercise.git
> $ cd front-end-developer-exercise
> $ npm install
```

#### Step 3 - Run!
Run the development server:
```
> $ npm start
```

#### Step 3 - View in browser
Open up your browser to http://localhost:5000/ and voila!

#### Notes
- The static CSS files you need are in `public/css`.
- The React files you need are in `src`
- When you edit CSS files, you will have to refresh the browser
- When you edit React files, the browser will automatically reflect your changes

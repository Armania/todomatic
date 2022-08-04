# READ ME

This is a sample react todo app based off of the [Developer.mozilla.org](https://developer.mozilla.org/) ['Getting started with React'](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_getting_started).

## Files in application

### Public Folder (/public)

This directory holds all the static files for this applicaton, most importantly the index.html file which serves this SPA (single page application).

- index.html, root file served for the SPA.
- manifest.json, to list all the pages associated with this application. (ignore)
- image directory, "/public/img/", is home to all of the graphics, including favicon, logos, and more.

### Source files (/src)

In the src directory you will find all the reactjs code used in this application

- App.js, which houses all the logic to run this app.
- index.css, the main style sheet home to all the main styles.
- index.js, the main root js file that creates our react application.
- Also, a reportWebVitals.js file, created with creat-react-app, used to share core web vital data.

### React Components (/src/components)

This application consists of 3 react components. All of which can be found in the './src/components/' directory

1. Form (Form.js), used to create new todo Items
2. Filter buttons (FilterButtons.js), to display a list of three filter buttons, "All", "Active" , and "Done".
3. Todo item (Todo.js), Which display all our todo items and corresponding input elements.

## Project Setup Inustructions

Download the content of this application and run the following command.

```sh
npm install
```

### To Start application

```sh
npm start
```

### Compile and Minify for Production

```sh
npm run build
```

# React practice

## What is react?

1. Displays HTML
2. Changes the HTML when user does something

We create functions in react and they return JSX which looks like HTML

Functions that return JSX are called **React Components**

A single project can have multiple components inside it

All react components that we create are going to return some JSX which tells react

1. create a normal HTML component
2. show another react component also called **Component Nesting**

## How does a react app start up

1. JS files are bundled together and placed on a server. A single HTML file is also placed on the server
2. User makes a request to the server and gets the HTML file + the bundle
3. User's browser executes your code
   a. React startup process
   b. find the div with the id root inside the DOM
   c. Tell react to take control of that element
   d. Tell react to get the JSX from the App component, turn it into HTML, and show it in the root

## What is useState() in React?

1. it is a function that works with React's state system
2. state is like a variable in React
3. state is used to store data that changes over time
4. whenever state changes, react automatically updates content on the screen

## How to create a react app?

```
npx create-react-app <project-name>
```

## How to start up your react project?

1. change into your project folder
2. `npm start`

## How to view your react project?

1. open your browser and navigate to localhost:3000

## How to stop your react project?

1. Press Control + C

## What are we running in our terminal

## what is JSX

JSX is not understood by browser so we need to first **transpile** it. transpile means to change one form of code to another form of code. the purpose of the command run into the terminal is to transpile this JSX into valid JS. we call this command running in the terminal to do this as **development server** or dev server for short.

the dev server:
babel --> Webpack --> bundle.js

babel: tool to turn jsx into normal js code
webpack: tool to merge all project files into a single file

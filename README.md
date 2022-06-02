# react-hook-form-repo
## Focused on 'react-hook-form' library that helps you validate forms in React.

### What is React Hook Form?

1. 'react-hook-form' is a library that helps you validate forms in React.
2. The package size is tiny (just 8.6 kB minified and gzipped) and it has zero dependencies.

### Commands to install?
- If npm: npm install react-hook-form
- If yarn: yarn add react-hook-form

### Register form data in react-hook-form:
#### useForm Hook? :
- import the useForm Hook from the react-hook-form package:
- `import { useForm } from "react-hook-form";`
- The useForm Hook returns an object containing a few properties like: register, handlesubmit..etc
- useForm Hook makes the component code cleaner and easier to maintain, and because the form is uncontrolled, you do not have to pass props like onChange and value to each input.

### Validate forms with react-hook-form?
- To apply validation to input fields we can pass validation parameters to the register
#### Properties of validation parameters:
- #### required:- indicates if the field is required or not. If this property is set to true, then the field cannot be empty
- #### minlength and maxlength:- set the minimum and maximum length for a string input value
- #### min and max:- set the minimum and maximum values for a numerical value
- #### type:- indicates the type of the input field; it can be email, number, text, or any other standard HTML input types
- #### pattern:- defines a pattern for the input value using a regular expression
# Implementation:

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
In the project directory:

### `npx create-react-app react-hook-form-demo`

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

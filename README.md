# Simple Data Reader

## First

- ### `npm install`

## Second

### In the project directory, you can run:

- ### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
<br />

## Third

### Project Guide

- Type your name in the Name field and you Age in the age field.
- Clicking `Submit` will parse the data to `userData` and push the data to the parent component and render out the inputed data.

### How it works

- Using the react hook `useState`, I was able to create a state that can store and hold object values, and another that would store the key strokes the user types into the input fields.
- Once the user clicks `Submit`, that data gets stored into the before mentioned variable, `userData`, then passed to the parent component with a props argument. Taking the information stored in `userData` and calling the function in the parent componment, `pullData`, that pulls the data and stores in another state variable `submittedUserData`. I then map through the array of `submittedUserData` and display that data as long as the object is not empty or equal to 0.

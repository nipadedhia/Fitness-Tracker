# Fitness Tracker

A fitness app that allows the user to view, create, and track daily workouts. The user is able to log multiple exercises in a given day and also go back and update the workout. The user is able to track the name, type, weight, sets, reps and duration of each exercise. Cardiovascular exercises show the distance traveled in miles..

## Description

- Created a fitness tracking app utilizing Node.js, Express.js, MongoDB, Heroku and Mongoose. Allows the user to track their workouts and save them in a database.

## Installation

You will need to npm init to get all the required node modules. If you are running the code locally the local host is set to port 3000. You will also need to go in to the config folder and possibly change the config.json values. The file I used to start the project is server.js.

## Approach

- Set up a server with a connection to a MongoDB database
- Define MongoDB schemas using Mongoose which will interact with the database
- Get user input about whether they want to create a new workout, or continue an existing one
- After choosing a workout, allow users to add new exercises to the workout
- Save the workout and the exercises to the database

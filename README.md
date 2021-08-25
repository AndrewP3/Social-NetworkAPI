# Social Network API

An API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. This application utilizes Express, Mongoose, and MongoDB to allow users to be create thoughts, as well as update and delete reactions.

## User Story

As s social media startup
I want an API for my social network that uses a NoSQL database so that my website can handle large amounts of unstructured data

## Walkthrough Video

<link>

## Acceptance Criteria

- GIVEN a social network API
- WHEN I enter the command to invoke the application
- THEN my server is started and the Mongoose models are synced to the MongoDB database
- WHEN I open API GET routes in Insomnia Core for users and thoughts
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
- THEN I am able to successfully create, update, and delete users and thoughts in my database
- WHEN I test API POST and DELETE routes in Insomnia Core
- THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Packages

- Express.js
- Mongoose
- MongoDB
- Moment

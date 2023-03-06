# About this app

This app takes a user-typed input and filters a list of users/robots received from the JSONPlaceholder API. Pictures of robots are generated using Robohash based on the unique id of the received user list. There are 2 actions: a synchronous action for handling user input and an asynchronous action (thunk) for handling the API call. The app is deployed on Netlify.
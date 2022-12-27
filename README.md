# Zyax frontend programming challenge 

## Assignment

Your task is to build a simple login form using React.js. The login form should have the following fields:

 - Email address
 - Password

The form should also have a submit button.

Once the user submits the form, you should send a request to the backend with the email and password. The backend will return an access and a refresh token if the login is successful, or an error if the login fails.

If the login is successful, you should store the access token in a cookie or local storage. If the login fails, you should display an error message to the user.

In addition, you should write tests for the login form using the React Testing Library. The tests should cover the following scenarios:

 - The form is initially rendered with empty fields.
 - The form displays an error message if the email address or password is blank.
 - The form displays an error message if the login fails.
 - The form stores the access token in a cookie or local storage if the login is successful.

You're free to use external packages, classes or functions and javascript or typescript. 

## Requirements

 - Use React.js to build the login form.
 - Send a POST request to the backend with the email and password when the user submits the form.
 - Store the access token in a cookie or local storage if the login is successful.
 - Display an error message to the user if the login fails.
 - Write tests for the login form using the React Testing Library or testing framework of choice. 

## Bonus

 - Add a logout button that removes the access token from the cookie or local storage.
 - Write tests for the logout button.

I hope this helps! Let me know if you have any questions.

## Delivery 
1. Assure that the project runs as intented; with Readme and all dependencies listed in package.json 
2. Upload the project to a public repo, or send the src-files to us (without node_modules/)
3. Send a short description of the project 
   1. What part did you struggle with? What part was easy? 
   2. Why were these parts easy/difficult? 
   3. What would you have done differently? 

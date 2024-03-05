#Bob_zico-project
Explanation:

HTML:
script.js is included in the head section for access to JavaScript functions.
The form has an id of "registrationForm" and uses the onsubmit event to call the validateForm() function upon submission.
Each input field has an id for easy access in JavaScript.
JavaScript:
The validateForm() function is called when the form is submitted.
It retrieves the values of all input elements using their IDs.
Each validation check uses an if statement:
Username length must be at least 3 characters.
Email address must follow a simple email pattern.
Password length must be at least 6 characters.
If any validation fails, an alert message is displayed, and the function returns false to prevent form submission.
If all validations pass, the function returns true, allowing the form to submit.

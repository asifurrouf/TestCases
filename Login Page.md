## Test Scenarios Login Page

1. Verify that the login screen is having option to enter username and password with submit button and option of forgot password
2. Verify that user is able to login with valid username and password
3. Verify that user is not able to login with invalid username and password
4. Verify that validation message gets displayed in case user leaves username or password field as blank
5. Verify that validation message is displayed in case user exceeds the character limit of the user name and password fields
6. Verify that there is reset button to clear the field's text
7. Verify if there is checkbox with label "remember password" in the login page
8. Verify that the password is in encrypted form when entered
9. Verify that there is limit on the total number of unsuccessful attempts
10. For security point of view, in case of in correct credentials user is displayed the message like "incorrect username or password" instead of exact message pointing at the field that is incorrect. As message like "incorrect username" will aid hacker in bruteforcing the fields one by one
11. Verify the timeout of the login session
12. Verify if the password can be copy-pasted or not
13. Verify that once logged in, clicking back button doesn't logout user
14. Verify if SQL Injection attacks works on login page
15. Verify if XSS vulnerability work on login page

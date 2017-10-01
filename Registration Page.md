## [Test scenarios for Registration Page](http://artoftesting.com/manualTesting/registration.html)

1. Verify that all the specified fields are present on the registration page
2. Verify that the required/mandatory fields are marked with * against the field
3. Verify that for better user interface dropdowns, radio buttons and checkboxes etc fields are displayed wherever possible instead of just textboxes
4. Verify the page has both submit and cancel/reset buttons at the end
5. Verify that clicking submit button after entering all the required fields, submits the data to the server
6. Verify that clicking cancel/reset button after entering all the required fields, cancels the submit request and resets all the fields
7. Verify that whenever possible validation should take place at client side
8. Verify that not filling the mandatory fields and clicking submit button will lead to validation error
9. Verify that not filling the optional fields and clicking submit button will still send data to server without any validation error
10. Check the upper limit of the textboxes
11. Check validation on date and email fields (only valid dates and valid email Ids should be allowed
12. Check validation on numeric fields by entering alphabets and special characters
13. Verify that leading and trailing spaces are trimmed
14. Verify that entering blank spaces on mandatory fields lead to validation error
15. Verify that after making a request to the server and then sending the same request again with the same unique key will lead to server side validation error

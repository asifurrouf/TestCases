In [this post](http://artoftesting.com/manualTesting/ecommerce.html) we will see some high level test cases of an e-commerce website covering general UI test cases, product buy flow test cases and product creation panel test cases.

## General Test Cases

1. Verify that user is able to navigate through all the products across different categories
2. Verify that all the links and banners are redirecting to correct product/category pages and none of the links arr broken
3. Verify that the company logo is clearly visible
4. Verify that all the text - product, category name, price and product description are clearly visible
5. Verify that all the images - product and banner are clearly visible
6. Verify that category pages have relevant product listed specific to the category
7. Verify that correct count of total products are listed on the category pages
8. Search - Verify that on searching all the product satisfying the search criteria are visble on the search result page
9. Search - Verify the more relevant product for the search term are displayed on the top for a particular search term
10. Search - Verify that count of products is correctly displayed on the search result page for a particular search term
11. Filtering - Verify that filtering functionality correctly filters product based on the filter applied
12. Filtering - Verify that filtering works correctly on category pages
13. Filtering - Verify that filtering works correctly on the search result page
14. Filtering - Verify that correct count of total products is displayed after a filter is applied
15. Sorting - Verify that all the sort options work correctly - correctly sort the products based on the sort option chosen
16. Sorting - Verify that sorting works correctly on the category pages
17. Sorting - Verify that sorting works correctly on the search result page
18. Sorting - Verify that sorting works correctly on the pages containing filtered result, after applying filters
19. Sorting - Verify that product count remains intact irrespective of sorting option applied

## Product Buy Flow - Test cases

1. Verify that on the product page, user can select the desired attribute of the product e.g. size, color etc
2. Verify that user can add to cart one or more products
3. Verify that user can add products to wishlist
4. Verify that user can buy products added to cart after signing in to the application (or as per the functionality of the website)
5. Verify that user can successfully buy more than one products that were added to his/her cart
6. Verify that user cannot add more than available inventory of the product
7. Verify that the limit to the number of products a user can by is working correctly by displaying error message and preventing user from buying more than the limit
8. Verify that the delivery can be declined of for the places where shipping is not available
9. Verify that Cash on Delivery option of payment is working fine
10. Verify that the different pre-paid methods of payments are working fine
11. Verify that product return functionality works fine

## User(Buyer) Registration - Test cases

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

## Seller - Product creation Test cases

1. Verify that authenticated sellers get access to product creation panel specific to the authorised categories
2. Verify that product creation panel is working fine for single product creation
3. Verify that product creation panel is working fine for multiple product creation
4. Verify that maximum product creation limit for seller is working fine, limiting seller to create more than the desired number of products
5. Verify panel validation for checking mandatory fields
6. Verify that duplicate product creation is restricted through panel
7. Verify that seller can update information and price of existing products
8. Verify that product created by seller get visible on the website after certain period of time
9. Verify that updation made by seller get visible on the website after certain period of time

In this post we will see some high level test cases of an e-commerce website covering general UI test cases, product buy flow test cases and product creation panel test cases.

## General Test Cases

* Verify that user is able to navigate through all the products across different categories
* Verify that all the links and banners are redirecting to correct product/category pages and none of the links arr broken
* Verify that the company logo is clearly visible
* Verify that all the text - product, category name, price and product description are clearly visible
* Verify that all the images - product and banner are clearly visible
* Verify that category pages have relevant product listed specific to the category
* Verify that correct count of total products are listed on the category pages
* Search - Verify that on searching all the product satisfying the search criteria are visble on the search result page
* Search - Verify the more relevant product for the search term are displayed on the top for a particular search term
* Search - Verify that count of products is correctly displayed on the search result page for a particular search term
* Filtering - Verify that filtering functionality correctly filters product based on the filter applied
* Filtering - Verify that filtering works correctly on category pages
* Filtering - Verify that filtering works correctly on the search result page
* Filtering - Verify that correct count of total products is displayed after a filter is applied
* Sorting - Verify that all the sort options work correctly - correctly sort the products based on the sort option chosen
* Sorting - Verify that sorting works correctly on the category pages
* Sorting - Verify that sorting works correctly on the search result page
* Sorting - Verify that sorting works correctly on the pages containing filtered result, after applying filters
* Sorting - Verify that product count remains intact irrespective of sorting option applied

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

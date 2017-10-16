### [Test scenarios of Google Search](http://artoftesting.com/manualTesting/google.html)

##Test Cases of Google Search

    Verify that the response fetched for a particular keyword is correct and related to the keyword, containing links to the particular webpage
    Verify that the response are sorted by relevancy in descending order i.e. most relevant result for the keyword are displayed on top
    Verify that response for multi word keyword is correct
    Verify that response for keywords containing alphanumeric and special characters is correct
    Verify that the link title, URL and description have the keyword highlighted in the response
    Verify auto-suggestion in Google e.g. providing input as 'fac' should give suggestions like 'facebook', 'facebook massenger', 'facebook chat' etc
    Verify that response fetched on selecting the suggested keyword and on providing the keyword directly should be same
    Verify that the suggestion provided by Google are sorted by most popular/relevant suggestions
    Verify that user can make search corresponding to different categories - web, images, videos, news, books etc and response should correspond to the keyword in that category only
    Verify that misspelled keyword should get corrected and response corresponding to the correct keyword should get displayed
    Verify that multi word misspelled keywords also get corrected
    Verify the performance of search- check if the time taken to fetch the response is within the ballpark
    Verify that total number of results fetched for a keyword
    Verify that the search response should be localised that is response should be more relevant to the country/area from which the search request is initiated
    Verify Google calculator service- make any arithmetic request, calculator should get displayed with correct result
    Verify Google converter service- make request like- 10USD in INR and check if the result is correct
    Verify search response for a large but valid strings
    Verify that incorrect keywords - keywords not having related result should lead to "did not match any documents" response
    Verify that user can make search using different languages
    Verify that for a keywords, some related search terms are also displayed to aid user's search
    Verify that for number of results more than the limit on a single page, pagination should be present, clicking on which user can navigate to subsequent page's result
    Verify Google's advanced search options like- searching within a website, searching for files of specific extension
    Verify if the search is case-insensitive or not
    Verify the functionality of "I'm feeling Lucky" search- the top most search result should get directly returned (but as of now google doodle page link is displayed)

## [Front End - UI Test Cases of Google Search](http://artoftesting.com/manualTesting/google.html)

    Verify that Google Logo is present and centre aligned
    Verify that the search textbox is centre aligned and editable
    Verify that search request should get hit by clicking on search button or hitting enter after writing the search term
    Verify that in the search result- webpage's title, URL and description are present
    Verify that clicking the search result will lead to the corresponding web page
    Verify that pagination is present in case number of results are greater than the maximum results allowed in a page
    Verify that user can navigate to a page number directly or move to previous or next page using the links present
    Verify that different languages links are present and gets applied on clicking the same
    Verify that the total number of results for the keyword is displayed
    Verify that the time taken to fetch the result is displayed


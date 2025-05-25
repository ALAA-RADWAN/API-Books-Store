# API-Books-Store

This API allows you to reserve a book.

The API is available at `https://simple-books-api.glitch.me`

First, I worked on the collection in Postman and used JavaScript to write the scripts. I implemented a full end-to-end scenario, from GET requests to DELETE.

I ran the collection using Postman Runner, but since the authentication required a new email every time, I solved that by creating a dynamic email using a timestamp I added in the Pre-request Script.

Then I exported the environment and the collection, and ran it using Newman from the command prompt, and displayed the results in a beautiful HTML report.

After that, I used the same collection with Rest Assured to apply automation using Java, along with Rest Assured, TestNG, and Jackson dependencies. 

Finally, I used Allure Report to display the results of the automation tests.

The resources I learned from:
 Postman: Valentine Despa | GitHub linkhttps://github.com/vdespa
 Rest Assured: Raghav | automationstepbystep.com

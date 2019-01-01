<h1>HW6 - GifTastic</h1>
<br>
<h2>This app displays buttons related to a certain topic and allows you to add search terms to generate additional buttons that when clicked, accesses the GIPHY API and generates 10 static GIPHY images. Click on an image to pause or play the GIF.</h2>
<h3>Requirements</h3>
<br>
<strong>The app takes the entered search term topics from a user input box and pushes them into array from which it creates buttons in the HTML. Clicking on a button grabs 10 static, non-animated gif images from the GIPHY API and places them on the page.</strong>
<br>
•	When the user clicks one of the still GIPHY images, the gif should animate.
•	If the user clicks the gif again, it should stop playing.
•	With every gif is displayed its rating (PG, G, etc.).
<br>
<h3>Technologies Used</h3>
<br>
•	HTML
•	CSS 
•	Bootstrap
•	JavaScript to make the page dynamic
•	jQuery for Dom Manipulation
•	AJAX for API GET requests
<br>
<h3>Code Explanation</h3>
<br>
•	A form was implemented to take the value from a user input box and add it into the topics array.
•	CSS Bootstrap was used to arrange the page into columns and display the gifs in a gallery format.
•	AJAX Call to Giphy's API was created to access the images by topic entered.
•	Event listeners on "click" were utilized 

<strong>If you Want to See Demo</strong> <a href = "https://nebiyouk.github.io/GifTastic" target = "_blank">Click Me</a>

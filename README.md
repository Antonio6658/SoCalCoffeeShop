# SoCalCoffeeShop
A webpage for SoCal Coffee Shop

## AI Disclosure
-I did not use generative AI tools for this project. I used only approved course materials, instructor examples, documentation, and my own work.

## Development Log

### Day 1
-Built HTML structure for content
-added the form, nav links, and sections.
-started adding the interactive sections for the product display and guessing game.
### Day 2
-worked on js validation and functions.
-Made sure functionality was present in productDisplay function, validateForm function, and guessing game function
-added styles for error messages and initial color selections and beginning style choices
-reformatted the product display into a function that adds and removes the .hide class to show the user what content they want, based on the button they click
-added more content for shop in html
-added fonts from google fonts
### Day 3
-worked on styling for entire page
-added images from unsplash
-added light and dark mode functionality
-added descriptive content for shop
-added licensing statements for fonts and images
-added comments for all code

## Debugging Log

### Problem 1
-I could not get the product pages to load after clicking the intended button.

### What I tried
-I commented out everything in the function and added them back piece by piece to see what the issue was.

### What fixed it
-I realized that I was using the wrong variable to access my event listener for latte and that I did not add the variable for the event listener, I changed the name to the appropriate variable, added the event listener for latte and the clicked button loaded the content

### What I learned
-To always be careful and double check my variables and that one incorrect variable in a function can cause the whole function to not operate correctly.

### Problem 2
-My form was submitting the phone number even if it had over 10 numbers

### What I tried
-I tried changing the aspects of the RegEx for the phone by adding anchors to the start and end of the string by using ^ and $ around the digits area.

### What fixed it
-Changing the RegEx to include the anchors and switching the input for the form phone number area from number to tel fixed the issue so it wouldn't submit the form unless there are 10 numbers entered by the user.

### What I learned
-Form validation needs to be specific, otherwise the incorrect information can be submitted or the form won't submit at all. I learned to always double check my regex by using regexr.com to test my expression to see if I am correct or not.

### Problem 3
-I struggled to get the dark mode to work properly

### What I tried
-I tried targeting specific styles for the function to target when the user clicked the toggle button. Such as changing the background color of the header main and footer.

### What fixed it 
-Targeting the root of CSS and adding a new section specifically for dark mode colors. I made sure to update the colors of all the text because the dark mode wasn't displaying properly
in some sections of content.

### What I learned
-I learned that if you choose your colors carefully, making a simple dark mode toggle is easy to accomplish and adds a welcomed change for all users. Also, to make sure to have accurate naming conventions
for content and that each one uses the variables that were created. 
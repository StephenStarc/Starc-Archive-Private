# Starc Archive Private

## Description
Starc Archive Private is a web-based application that displays a table of daily processes or tasks. It a clone of daily Progress Checker and all the functionality are same.
Just like Daily Process Checker, i use this repo to add new things i learn everyday but link stored in this archive is private and only access by me.

Yes, I might learn things that i want to but i am not proud of. So i'll add all my progress here.
You might wonder, if you want this private, why don't just make the repo private.
That's a great question, Well github free version doesn't allow you host the private repo pages.

So, yeah here we are. i want to see all data in simple site. so used the pubilc repo and hosted the site on github pages and made other links as a private gated content.

## Features
- Responsive table layout
- Dynamic data loading from a JavaScript file
- Cool animations and hover effects
- Gradient background with frosted glass effect card

## File Structure
- `index.html`: Main HTML file
- `styles.css`: CSS styles for the application
- `data.js`: JavaScript file containing the data for the table (not included in this repository)
- `logo.jpg`: Logo image file (not included in this repository)

## Setup
1. Clone this repository to your local machine.
2. Ensure you have a `data.js` file in the same directory with the following structure:
   ```javascript
   const data = [
     {
       slno: 1,
       title: "Example Title",
       category: "Example Category",
       date: "2024-03-15",
       blogLink: "https://example.com"
     },
     // Add more objects as needed
   ];
   ```
3. Add your `logo.jpg` file to the same directory.
4. Open `index.html` in a web browser to view the application.

## Customization
- To change the color scheme, modify the CSS variables in the `styles.css` file.
- To add or remove columns, update the table structure in `index.html` and adjust the data loading script accordingly.

## Dependencies
- Bootstrap 5.3.3
- jQuery 1.10.2

## Browser Compatibility
This application is designed to work on modern web browsers. For the best experience, use the latest versions of Chrome, Firefox, Safari, or Edge.

## Notes
This is a private archive. Please ensure that sensitive data in `data.js` is properly secured and not shared publicly.

## Author
Stephen Starc

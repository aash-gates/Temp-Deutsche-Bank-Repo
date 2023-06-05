# Code Modifications README

This README file provides an overview of the changes and updates made to the codebase.

## Contents

- index.html (Main File that has to linked from the mentioned button)
- Changed from multiple page to single long scroll page
- Created for Deutsche Bank 
- Created by Aashik J Krishnan Socially Known as Aash Gates
## Description

The code modifications in this project aim to enhance the functionality and user experience of the application. Various improvements have been implemented to achieve the desired outcomes.

## Changes

1. Added a script to open a PDF in a new browser window:
   - Created a JavaScript function `openPDF()` to open the PDF in a new window.
   - Used the `window.open()` method to open the PDF file in a new browser window.
   - Added a timer to automatically close the PDF window after a specific duration.
   - Implemented an event listener to close the PDF window when the user clicks outside of it.

2. Modified the "Back" button to scroll further on click:
   - Updated the button's behavior to scroll the page by a specific distance.
   - Replaced the `href` attribute with `javascript:void(0)` to prevent the page from navigating to a different URL.
   - Added the `onclick` attribute to execute the `openPDF()` function when the button is clicked.

3. Modified from Multiple Page to Single Long Scroll page
   - As per the client requirement the page was converted to single page
   - created table under the main Button and linked to the PDF
   - PDF are opened in new window and are closed automatically after 3 mins

## Usage

To use the code modifications:

1. Include the updated JavaScript code in your project.
2. Place the modified HTML code in your HTML file.
3. Customize the code as per your requirements, such as changing the PDF file path, adjusting the scroll distance, etc.
4. Test the functionality of the "Back" button and the PDF window.

Feel free to explore and modify the code to fit your specific needs. If you encounter any issues or have further questions, please reach out for assistance.


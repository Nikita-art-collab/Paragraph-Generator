# Random Paragraph Generator

## Overview

This project is a simple web application that generates a specified number of random paragraphs on a button click. It is built using HTML, CSS, and JavaScript.

## Features

- Users can input a number to generate that many random paragraphs.
- The paragraphs are shuffled randomly from a predefined list.
- Responsive and user-friendly design with basic styling.

## File Structure

- **index.html**: The main HTML file that contains the structure of the webpage.
- **style.css**: The stylesheet that provides the visual design for the page.
- **script.js**: The JavaScript file that handles the logic for generating and displaying the random paragraphs.

## How to Use

1. Open `index.html` in your web browser.
2. Enter the number of paragraphs you want to generate in the input field (default is 5).
3. Click the "Generate" button.
4. Random paragraphs will appear on the screen below the button.

## Dependencies

No external libraries or dependencies are required to run this project. It uses vanilla HTML, CSS, and JavaScript.

## Project Files

- **index.html**: Sets up the webpage layout and links to the external CSS and JavaScript files. It includes an input field for selecting the number of paragraphs and a button to trigger the paragraph generation.
  
- **script.js**: Contains the logic for:
  - Shuffling the list of paragraphs.
  - Displaying the selected number of paragraphs.
  - Handling cases where the input number is zero or exceeds the available number of paragraphs.
  
- **style.css**: Styles the webpage with a gradient background, card layout, and responsive input/button designs.

## Example

When a user enters `3` in the input field and clicks "Generate", three random paragraphs from the predefined list are displayed below the input section.

## Known Issues

- If the number entered exceeds the available paragraphs, the application will return only one random paragraph.

## Future Enhancements

- Add more paragraphs to the list.
- Improve error handling for invalid inputs.
- Make the application mobile-friendly by adding responsive design improvements.


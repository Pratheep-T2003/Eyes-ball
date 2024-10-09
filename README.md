README for Coding Assignment 7: Eye Tracking Animation
Overview
This project is a simple web-based animation that simulates eye movement. The animation features two "eyes" that follow the mouse cursor as it moves across the screen. The project leverages HTML, CSS, and JavaScript to create an interactive experience.
Table of Contents
1.	Features
2.	Technologies
3.	Installation
4.	Usage
5.	How It Works
6.	Contributing
7.	License
Features
•	Two animated eyes that follow the mouse movements in real-time.
•	Simple and responsive design.
•	Easy to extend and customize further.
Technologies
•	HTML: For structuring the content.
•	CSS: For styling the eyes and the page layout.
•	JavaScript: For handling mouse events and animating eye movements.
Installation
To run this project locally, follow these steps:
1.	Copy the HTML code provided in the assignment into a new file named index.html.
2.	Open the index.html file in any modern web browser (Chrome, Firefox, Safari, etc.).
Usage
•	Move your mouse within the browser window, and observe how the eyes follow the cursor smoothly.
•	Feel free to modify the CSS for different eye colors, sizes, or other stylistic changes.
How It Works
1.	The HTML structure consists of a div for the eyes, which contains nested div elements for the eyeballs.
2.	CSS styles are applied to create a clean appearance and position the eyes on the screen.
3.	A JavaScript function (move) is executed whenever the mouse moves over the body of the page. This function calculates the position of the mouse relative to each eyeball and applies a transformation to simulate the eyeballs moving towards the cursor.
Key JavaScript Functionality
•	The function move(item) captures the mouse event and retrieves the cursor's position using item.pageX and item.pageY.
•	The offsets of each eyeball are calculated to position them correctly relative to the mouse cursor.
•	The eyeballs are then moved using the style.transform property with a translate3d transformation.
Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your enhancements or fixes. Contributions that improve the project or add new features are welcome!
License
This project is open-source and available under the MIT License. You can modify and distribute it freely, but please keep this notice intact.

# temperature-converter
1. Project Overview:
The individual project is a Temperature Converter web application. The primary purpose of this application is to allow users to convert temperatures between Celsius and Fahrenheit. Users can input a temperature value and select the unit (Celsius or Fahrenheit), and the application will provide the converted temperature.

2. Project Implementation:
HTML and CSS:
The project uses HTML to structure the web page, including a form with input fields and a result section.
CSS is utilized for styling the user interface, providing a visually appealing and responsive design.
JavaScript:
The core functionality is implemented in JavaScript.
The convertTemperature function is triggered on form submission to handle the conversion logic.
The function checks whether Celsius or Fahrenheit is selected and performs the corresponding temperature conversion.
The result is then displayed in the designated result section.
Logic:
The conversion formulas are standard:
Celsius to Fahrenheit: (Celsius * 9/5) + 32
Fahrenheit to Celsius: (Fahrenheit - 32) * 5/9
The toFixed(1) method is used to round the result to one decimal place.
Error Handling:
An alert is displayed if the user tries to submit the form without selecting a temperature unit.
3. Tools Used:
HTML/CSS: Used for structuring the webpage and styling the user interface.
JavaScript: The core programming language for implementing the temperature conversion logic and handling user interactions.
Text Editor: A text editor (e.g., Visual Studio Code, Sublime Text) was likely used for coding.
4. Additional Information:
Responsive Design: The CSS includes media queries to ensure a responsive design, adapting to different screen sizes.
Degree Symbol: To display the degree symbol in the result, the ° character is used directly within the textContent.
Summary:
The Temperature Converter project is a web application that provides a simple and intuitive interface for users to convert temperatures. It leverages the fundamental web technologies (HTML, CSS, and JavaScript) to deliver a functional and aesthetically pleasing user experience. The project showcases skills in front-end web development, including user interface design and interactive form handling.

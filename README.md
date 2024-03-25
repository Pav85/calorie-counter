![image](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![image](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![image](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

# Calorie Counter Application

The Calorie Counter Application is a simple web tool designed to help users track their daily calorie intake against their set budget. By inputting calories consumed for different meals and exercises performed, users can calculate their remaining calorie budget for the day. This README outlines the features of the application and guides on how to set it up and use it.

## Features

- **Daily Calorie Budget**: Set a daily calorie budget to manage your calorie intake.
- **Meal and Exercise Entries**: Add entries for breakfast, lunch, dinner, snacks, and exercises with their respective calorie values.
- **Dynamic Entry Addition**: Dynamically add new food or exercise entries within each category.
- **Calorie Calculation**: Calculate the total consumed calories against the budget and display the surplus or deficit.
- **Form Validation**: Validates input to ensure that only numeric values are entered for calorie counts.
- **Clear Form**: Allows users to clear all input fields and start fresh.

## Setup and Deployment

The application is deployed and can be accessed online, allowing users to immediately start tracking their calorie intake without any setup required.

- **Live Application**: [Calorie Counter Live App](https://pav85.github.io/calorie-counter/)
- **Source Code**: The source code for the application is available on GitHub. You can view, download, or contribute to the project using the following link: [GitHub Repository](https://github.com/Pav85/calorie-counter)

## Usage

1. **Set a Daily Budget**: Enter your daily calorie budget in the provided input field.

2. **Add Entries**: Select a category from the dropdown (Breakfast, Lunch, Dinner, Snacks, Exercise) and click "Add Entry" to add a new entry field for that category.

3. **Input Calories**: For each entry, input the name (optional) and the calorie value.

4. **Calculate Remaining Calories**: Click on "Calculate Remaining Calories" to see your daily calorie intake, how it compares to your budget, and whether you are in a surplus or deficit.

5. **Clear Form**: Use the "Clear" button to reset all fields and start over.

## Important Functions

- `cleanInputString()`: Cleans the input string by removing any unwanted characters.
- `isInvalidInput()`: Checks for invalid inputs, such as exponential numbers, to prevent errors in calculations.
- `addEntry()`: Adds a new entry field for the selected category.
- `calculateCalories()`: Calculates the total calorie intake and compares it with the budget to display the result.
- `getCaloriesFromInputs()`: Gathers calorie inputs from all entry fields and calculates the total.
- `clearForm()`: Clears all input fields and resets the form.

## Event Listeners

- `Add Entry Button`: Adds a new entry field for the selected category.
- `Calculate Calories Button`: Initiates the calorie calculation process.
- `Clear Form Button`: Clears the form for a fresh start.

Ensure you include the JavaScript file at the end of your HTML file to properly load the script after the HTML content.

 

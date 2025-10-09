# JavaScript Programming Assignment - Lab 03

**Student:** Rao Anas  
**Enrollment:** 02-134231-065  
**Course:** SEL 310: Web Engineering Lab  
**Lab Engineer:** Mr. Muhammad Osama  

## Project Overview

This project implements a comprehensive JavaScript programming assignment featuring 7 exercises that demonstrate fundamental JavaScript concepts. The implementation uses pure vanilla JavaScript with HTML and CSS, exactly as a student would code these exercises using prompt() and alert() functions.

## Project Structure

```
vanilla-js-assignment/
├── index.html                 # Homepage with exercise links
├── style.css                  # Main stylesheet
├── script.js                  # General scripts (if any)
├── tasks/
│   ├── age-calculator.html
│   ├── temperature-converter.html
│   ├── bmi-categorization.html
│   ├── bmi-pounds.html
│   ├── guess-the-number.html
│   ├── student-grades.html
│   └── daily-utilities.html
└── README.md
```

## Implemented Exercises

### Exercise 1: Age Calculator
- **Concepts:** Variables, prompts, alerts, arithmetic operators, conditionals, Date object
- **Features:**
  - Ask user for name and birth year
  - Calculate age using current year
  - Adult/minor classification (≥18 = Adult, <18 = Minor)
  - Input validation (empty, non-numeric, future year)

### Exercise 2: Temperature Converter
- **Concepts:** Prompts, math operations, input validation
- **Features:**
  - User choice selection via prompt
  - Fahrenheit to Celsius: (°F − 32) ÷ 1.8 = °C
  - Celsius to Fahrenheit: (°C × 1.8) + 32 = °F
  - Display results with 2 decimal places
  - Handle invalid inputs (NaN, empty, cancel)

### Exercise 3: BMI Categorization
- **Concepts:** Math operations, conditionals, health categories
- **Features:**
  - Calculate BMI using metric units (kg, meters)
  - Categorize according to CDC guidelines:
    - Below 18.5: Underweight
    - 18.5 – 24.9: Normal
    - 25.0 – 29.9: Overweight
    - 30.0 and above: Obese
  - Input validation for weight and height

### Exercise 4: BMI Calculation (Imperial Units)
- **Concepts:** Unit conversion, math operations, validation
- **Features:**
  - Calculate BMI using pounds and inches
  - Formula: (weight in lbs × 703) ÷ (height in inches)²
  - Round result to tenths (1 decimal place)
  - Convert height display to feet and inches
  - Input validation

### Exercise 5: Guess the Number Game
- **Concepts:** Random numbers, loops, conditionals, break, flags
- **Features:**
  - Generate random number between 1-10
  - Give user 3 attempts to guess
  - Show hints "Too High" or "Too Low"
  - End game if attempts run out or user cancels
  - Input validation for guess range

### Exercise 6: Student Marks & Grade System
- **Concepts:** Arrays, loops, grade calculation, validation
- **Features:**
  - Array of 5 subjects: ["Mathematics", "English", "Science", "History", "Computer Science"]
  - Ask user to enter marks for each subject
  - Calculate total, percentage, and assign grade:
    - ≥ 80: Grade A
    - ≥ 60: Grade B
    - < 60: Fail
  - Handle invalid marks (negative, >100, non-numeric)
  - Display formatted result

### Exercise 7: Daily Utilities Toolkit
- **Concepts:** Menu systems, string manipulation, arrays, date formatting
- **Features:**
  - Menu-driven interface with 6 options:
    1. Format Name (capitalize first letter of each word)
    2. Generate Random 4-digit OTP
    3. Search City in array ["Karachi", "Lahore", "Islamabad"]
    4. Show Today's Date in dd/mm/yyyy format
    5. Mini Calculator (add, subtract, multiply, divide)
    6. Exit
  - Handle invalid options and edge cases (division by zero)
  - Loop until user chooses to exit

## Technical Implementation

### Pure Vanilla JavaScript
- **No Frameworks:** Uses only HTML, CSS, and vanilla JavaScript
- **Student-Style Coding:** Simple, clear code structure as a student would write
- **Prompt/Alert Interface:** All user interaction through prompt() and alert() functions
- **Input Validation:** Comprehensive validation for all user inputs
- **Error Handling:** Proper error handling and user feedback

### Code Quality Features
- **Clear Variable Names:** Descriptive variable names for readability
- **Comments:** Well-commented code explaining logic
- **Consistent Structure:** Uniform code structure across all exercises
- **Input Validation:** Robust validation for all user inputs
- **Error Messages:** Clear, helpful error messages for users

### Web Interface
- **Clean Layout:** Professional homepage with exercise cards
- **Navigation:** Easy navigation between exercises and back to homepage
- **Responsive Design:** Works on different screen sizes
- **Code Display:** Each exercise page shows the complete JavaScript code
- **Professional Styling:** Clean, academic styling appropriate for assignment submission

## Assignment Requirements Compliance

✅ **Exercise 1:** Age Calculator with name, birth year, adult/minor classification  
✅ **Exercise 2:** Temperature Converter with user choice and 2 decimal places  
✅ **Exercise 3:** BMI Categorization with CDC guidelines  
✅ **Exercise 4:** BMI Calculation using imperial units (pounds/inches)  
✅ **Exercise 5:** Guess the Number game with random numbers, loops, hints  
✅ **Exercise 6:** Student Grade System with 5 subjects, arrays, grade calculation  
✅ **Exercise 7:** Daily Utilities Toolkit with menu system and multiple functions  

✅ **All inputs via prompt()** as specified in requirements  
✅ **All outputs via alert()** as specified in requirements  
✅ **Proper input validation** for all exercises  
✅ **Error handling** for edge cases  
✅ **Student-style coding** with clear, simple structure  
✅ **Well-structured project** with homepage and dedicated pages  
✅ **Professional layout** with header and footer  

## How to Use

1. Open `index.html` in a web browser
2. Click on any exercise card to navigate to that exercise
3. Click the "Run" button to execute the JavaScript code
4. Follow the prompts to interact with each exercise
5. Use the "Back to Home" button to return to the main page

## Technologies Used

- **HTML5:** Structure and content
- **CSS3:** Styling and layout
- **Vanilla JavaScript:** All programming logic and interactivity
- **No external libraries or frameworks**

## Learning Outcomes Demonstrated

This assignment successfully demonstrates:
- Fundamental JavaScript programming concepts
- User input/output handling with prompt() and alert()
- Data validation and error handling
- Control structures (loops, conditionals)
- Functions and modular programming
- Arrays and string manipulation
- Mathematical operations and calculations
- Menu-driven programming
- Clean, readable code structure

---

**Assignment completed successfully with all requirements met using pure vanilla JavaScript implementation.**

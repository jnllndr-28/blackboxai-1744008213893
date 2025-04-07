
Built by https://www.blackbox.ai

---

# Geologic Timescale Quiz

## Project Overview
The Geologic Timescale Quiz is an interactive web application designed to test users' knowledge of Earth's geological history. With a series of 10 multiple-choice questions, this quiz covers major eras, periods, and significant events that have shaped our planet over its 4.6 billion-year history. The application provides immediate feedback on answers, along with explanations for each question.

## Installation
To set up the Geologic Timescale Quiz locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/geologic-timescale-quiz.git
   cd geologic-timescale-quiz
   ```

2. **Open `index.html` in a web browser**:
   Simply double-click the `index.html` file or open it with your preferred web browser to start using the quiz.

## Usage
- Start the quiz by clicking the "Start Quiz" button on the homepage.
- Navigate through the questions using the "Next Question" button.
- After completing the quiz, review your score and the correct answers on the results page.
- You can retake the quiz by clicking on the "Try Again" button.

## Features
- A user-friendly interface built with [Tailwind CSS](https://tailwindcss.com/).
- Dynamic question loading from a JSON file, providing a wide array of possible quiz questions.
- Instant feedback on answers, along with additional explanations for each question.
- Responsive design ensures compatibility across various devices.

## Dependencies
The project relies on the following external libraries:
- **Tailwind CSS**: For styling the application.
- **Font Awesome**: For icons used in navigation and buttons.

These libraries are linked directly in the HTML files and do not require additional installation.

## Project Structure
```
geologic-timescale-quiz/
│
├── index.html       # Main landing page for the quiz
├── quiz.html        # The interactive quiz page
├── results.html     # Page displaying the results and scores
├── questions.json    # JSON file containing quiz questions and answers
└── style.css        # Custom styles for the quiz (if needed)
└── script.js        # JavaScript for quiz functionality
```

Feel free to explore the code, customize the questions in `questions.json`, or improve the design in `style.css`. Happy quizzing!
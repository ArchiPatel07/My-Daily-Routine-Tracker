## My Daily Routine Tracker
***Project Overview***
My Daily Routine Tracker is a Python-based command-line project designed to help students and professionals track their daily activities. It records study hours, college hours, sleep, screen time, and mood, providing analysis, insights, and suggestions to improve productivity and maintain a balanced lifestyle. The project is simple to run, requires no GUI, and works entirely from the terminal.
***Features***
Add daily entries including study hours, college time, sleep, screen time, and mood.
View all recorded entries in a clear format.
Analyze data to get averages, productivity scores, mood distribution, and insights.
Delete entries that are no longer needed.
Predict mood based on current routine and get personalized suggestions.
Weekly summary for reviewing the last 7 days.
Motivation quotes to encourage good habits.
***Project Structure***
proj AI ML → Python scripts (main.py)
Project_file.docx → Project report
README.md → This file
***Prerequisites***
Python 3.8 or higher
No external libraries required (pure Python)
***Setup Instructions***
Clone the repository: Open your terminal and type
git clone https://github.com/ArchiPatel07/My-Daily-Routine-Tracker.git
Navigate to the project folder:
cd My-Daily-Routine-Tracker/proj AI ML
Dependencies: None required. All functionality uses Python’s built-in libraries.
***How to Run the Project***
Ensure you are in the proj AI ML folder.
Run the main program: python main.py
Use the interactive menu to perform actions:
Add Entry
View Entries
Analyze Data
Delete Entry
Predict Mood
Weekly Summary
Motivation
Exit
Follow the prompts to input data. Numbers cannot be negative, and mood must be one of: happy, normal, tired, stressed.
****Data File****
All entries are stored in data.json located in the same folder as the script.
The code automatically handles the file path, so it works even if you run the script from a different directory.
If the file doesn’t exist, it will be created automatically.
***Notes for Evaluator***
Fully executable via command line only.
At least 3 entries are required for mood prediction.
At least 7 entries are required for the weekly summary.
Input validations are included to prevent errors.

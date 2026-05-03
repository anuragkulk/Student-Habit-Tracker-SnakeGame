Python Project Portfolio

A collection of diverse Python projects ranging from Data Science and Machine Learning to interactive Game Development.

🚀 Projects Overview

1. Students Habits & Performance Tracker

File: students_habits_tracker.py

Category: Data Science / Machine Learning

This project analyzes the relationship between various student habits and their academic performance. It uses a regression-based approach to predict exam scores based on features like study hours, sleep, and diet.

Key Features:

Exploratory Data Analysis (EDA): Statistical summaries, histograms, and box plots to understand data distribution.

Data Cleaning: Automatic outlier removal using the Interquartile Range (IQR) method.

Feature Engineering: Encoding categorical variables and scaling numerical features.

Model Comparison: Implements and evaluates multiple models:

Linear Regression (Best Performer)

Random Forest Regressor

Support Vector Regressor (SVR)

Evaluation Metrics: R-squared and Adjusted R-squared scores.

2. Retro Snake Arcade Game

File: SNAKE GAME.py

Category: Game Development

A polished, object-oriented implementation of the classic Snake game built using the pygame library.

Key Features:

Smooth Mechanics: Vector-based movement and logic for snake growth and fruit spawning.

Visual Enhancements: Custom graphics for the snake's head, body, and tail, varying based on movement direction.

Audio Integration: Sound effects for eating and game-over states.

State Management: High-score tracking, game-over screens, and a "Restart" functionality.

Responsive Controls: Grid-based movement with collision detection for walls and self.

🛠 Installation & Requirements

To run these projects, you need Python installed on your system. You can install the necessary dependencies using pip:

pip install pandas numpy matplotlib seaborn scikit-learn pygame


📖 How to Use

Students Habits Tracker

Ensure the dataset student_habits_performance.csv is in the same directory as the script.

Run the script:

python students_habits_tracker.py


The script will output statistical plots and the final model performance scores.

Snake Game

Ensure you have the Graphics/, Sound/, and Font/ folders in the project directory.

Run the game:

python "SNAKE GAME.py"


Use the Arrow Keys to move. Press R to restart or Q to quit after a game over.

📧 Contact

Feel free to reach out if you have any questions or suggestions regarding these projects!

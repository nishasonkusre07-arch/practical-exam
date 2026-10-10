# 🏃‍♀️ Fitness Tracker System 💪
### 🌟 Track Your Activities • Analyze Your Progress • Stay Healthy

---

## 📌 Project Overview

The **Fitness Tracker System** is a Python-based application developed to record, manage, and analyze fitness activities. It provides a simple menu-driven interface that allows users to store workout details, calculate calories burned, analyze workout duration, and generate fitness reports.

The project uses Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn** to perform data processing, numerical calculations, and graphical visualization.

Fitness information is stored in a CSV file, making it possible to load previously saved workout records whenever the program is started again.

This project is useful for students who want to practice Python programming, Object-Oriented Programming (OOP), data analysis, file handling, and visualization in a single application.

---

## 🎯 Project Objectives

The main objectives of this project are:

- 📝 To record daily workout activities.
- 📂 To store and manage fitness information using CSV files.
- 🔥 To calculate total calories burned.
- ⏱️ To analyze workout duration.
- 📊 To calculate useful fitness statistics.
- 🔍 To search and filter specific activities.
- 📅 To generate weekly fitness summaries.
- 📈 To represent fitness data using different charts.
- 🧮 To apply NumPy for numerical analysis.
- 🐼 To use Pandas for data processing and manipulation.
- 🎓 To improve practical Python programming skills.

---

## ✨ Key Features

### 📝 1. Add Fitness Activity

Users can enter the following information for each workout:

- 📅 Workout date
- 🏃 Activity type
- ⏱️ Duration in minutes
- 🔥 Calories burned

The entered activity is added to the dataset and saved in the CSV file.

### 📋 2. View All Activities

Displays all recorded workout activities in a structured table. Users can review their previous workout details in one place.

### 🔥 3. Total Calories Burned

Calculates the total calories burned across all recorded activities. This provides an overall summary of the calorie information entered by the user.

### ⏱️ 4. Average Workout Duration

Calculates the average duration of recorded workouts using the workout-duration data.

### 📊 5. Activity Frequency Analysis

Displays the number of times each activity appears in the dataset. This helps identify which activities have been recorded most frequently.

### 🧮 6. NumPy Statistical Analysis

Uses NumPy arrays and statistical functions to calculate:

- Average calories burned
- Maximum calories burned
- Minimum calories burned
- Total calories burned
- Average workout duration
- Maximum workout duration
- Minimum workout duration

### 📅 7. Weekly Fitness Report

Groups recorded activities by week and calculates the total workout duration and calories burned for each week.

### 🔍 8. Filter Activities

Allows users to search for a particular activity, such as Running, Walking, Cycling, Swimming, or Yoga.

The program displays matching records when available.

### 🏆 9. Fitness Report

Generates a fitness summary containing:

- Total number of activities
- Total workout duration
- Total calories burned
- Average calories burned
- Most common activity

### 📈 10. Data Visualization

The project includes four visualization options to make fitness information easier to understand.

---

## 📊 Charts and Visualization

### 📊 Bar Chart

Displays the total workout duration for each activity. It helps compare the amount of time recorded for different workouts.

### 📉 Line Chart

Shows calories burned over time. It helps visualize changes in the recorded calorie data across dates.

### 🥧 Pie Chart

Represents the distribution of recorded calories burned across different activity types.

### 🌡️ Heatmap

Displays calories burned by activity and date using different shades, making patterns in the dataset easier to observe.

---

## 🏋️ Supported Fitness Activities

The application supports the following activity types:

| No. | Activity | Emoji |
|---:|---|:---:|
| 1 | Running | 🏃 |
| 2 | Walking | 🚶 |
| 3 | Cycling | 🚴 |
| 4 | Yoga | 🧘 |
| 5 | Gym | 🏋️ |
| 6 | Swimming | 🏊 |
| 7 | HIIT | 💥 |
| 8 | Strength Training | 💪 |
| 9 | Stretching | 🤸 |

Only the activity types defined in the program are accepted.

---

## 🛠️ Technologies and Libraries Used

### 🐍 Python

Python is the main programming language used to build the application and implement its functionality.

### 🐼 Pandas

Pandas is used to read CSV data, create DataFrames, clean records, filter activities, group data, and calculate summaries.

### 🔢 NumPy

NumPy is used for numerical calculations and statistical analysis, including mean, minimum, maximum, and sum.

### 📊 Matplotlib

Matplotlib is used to create bar charts, line charts, and pie charts.

### 🎨 Seaborn

Seaborn is used to create the heatmap and visualize relationships within the fitness dataset.

### 📁 CSV File Handling

CSV files are used to store fitness records in a simple tabular format that can be opened using spreadsheet applications.

---

## 🧠 Python Concepts Implemented

This project demonstrates several important Python concepts:

- 📦 Importing and using modules
- 🧱 Classes and objects
- 🏗️ Constructors using `__init__()`
- 🔧 Functions and methods
- 🔁 `while` loops
- 🔀 `if`, `elif`, and `else` statements
- 🛡️ Exception handling using `try` and `except`
- 📂 File handling
- 📋 Lists and sets
- 🗂️ Dictionaries and DataFrames
- 🔍 Searching and filtering
- 🧮 Numerical calculations
- 📊 Data grouping and aggregation
- 📈 Data visualization

---

## 🔄 Project Workflow

The application follows this general workflow:

1. 🚀 Start the Python program.
2. 📂 Load existing fitness records from the CSV file.
3. 📋 Display the main menu.
4. 🎯 Select an available operation.
5. 📝 Add, view, search, or analyze workout records.
6. 🧮 Calculate statistics using Pandas and NumPy.
7. 📈 Generate charts when required.
8. 💾 Save new activity records to the CSV file.
9. 🚪 Exit the application.

---

## 📂 Project Structure

```text
Fitness_Tracker_Project/
│
├── Fitness_Tracker.py
├── Fitness_activities.csv
└── README.md
```

**File descriptions:**

- `Fitness_Tracker.py` — Contains the main Python program, class methods, analysis functions, and chart options.
- `Fitness_activities.csv` — Stores the fitness activity records.
- `README.md` — Provides project documentation, features, installation instructions, and usage information.

The CSV file is created automatically if it does not exist when the program starts.

---

## ⚙️ Installation and Setup

### Step 1️⃣: Install Python

Install Python on your computer and make sure it can be run from your terminal.

### Step 2️⃣: Open the Project Folder

Open the project folder in Visual Studio Code or another Python editor.

### Step 3️⃣: Install Required Libraries

Run the following command in the terminal:

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 4️⃣: Run the Program

Execute the following command:

```bash
python Fitness_Tracker.py
```

### Step 5️⃣: Use the Application

Follow the on-screen menu to add activities, view records, calculate statistics, generate reports, and display charts.

---

## 💾 Data Storage and Management

The project stores its data in `Fitness_activities.csv`.

The CSV file contains these columns:

- `Datetime` — Date of the fitness activity.
- `Activity Type` — Name of the workout.
- `Duration (Minutes)` — Duration of the workout.
- `Calories Burned` — Calorie value entered for the activity.

The program reads saved data when it starts and writes updated records when a new activity is added.

This approach provides a simple way to retain workout records without requiring a database server.

---

## 🌟 Benefits of the Project

- ✅ Simple menu-driven interface
- ✅ Easy fitness record management
- ✅ Organized CSV data storage
- ✅ Useful numerical summaries
- ✅ Multiple chart options
- ✅ Practice with real-world data handling
- ✅ Demonstrates multiple Python libraries
- ✅ Suitable for Python learning and college projects
- ✅ Combines OOP, data analysis, and visualization

---

## 🎓 Learning Outcomes

After completing this project, learners can gain practical experience in:

1. Developing a menu-driven Python application.
2. Organizing program functionality using classes and methods.
3. Reading and writing CSV files.
4. Processing tabular data with Pandas.
5. Performing statistical calculations with NumPy.
6. Creating data visualizations with Matplotlib and Seaborn.
7. Handling invalid input and file-reading errors.
8. Grouping and filtering records for reports.
9. Understanding the workflow of a small data-analysis project.

---

## 🔮 Future Enhancements

The project can be extended with additional features in the future:

- 👤 Multiple user profiles
- 🔐 User login and authentication
- 🎯 Daily and weekly workout goals
- 📅 Monthly and yearly reports
- 📊 Interactive fitness dashboard
- 📈 Workout progress comparison
- 🗄️ Database integration using SQLite or MySQL
- 🖥️ Graphical user interface using Tkinter
- 🌐 Web-based application
- 📤 Export reports to Excel or PDF
- 🔔 Workout reminders
- 🏅 Achievement badges and milestones

These enhancements could make the system more interactive and convenient to use.

---

## ⚠️ Important Notes

- 📌 Enter dates in `YYYY-MM-DD` format.
- 📌 Use the activity names supported by the program.
- 📌 Enter positive values for workout duration and calories.
- 📌 Keep the CSV file in the correct project folder.
- 📌 Install the required libraries before running the application.
- 📌 Calorie values are user-entered records and are not automatically calculated by the current program.
- 📌 Fitness summaries describe the data entered; they are not medical or professional fitness assessments.

---

## connect with me:

linkedin : www.linkedin.com/in/nisha-sonkusre-283526415
g-mail : nishasonkusre07@gmail.com

---



⭐ **If you find this project useful, consider giving the repository a star on GitHub!**

Made with ❤️ and Python 🐍

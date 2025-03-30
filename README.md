# 🧠 The Quiz Project 🎯  
An interactive, Python-based quiz application that tests users’ knowledge through multiple-choice questions. This project follows a structured approach using object-oriented programming (OOP) concepts and modular design to create an efficient and reusable quiz system.

## 🔥 Key Features  

### 📌 Object-Oriented Programming (OOP)  
The project is structured around classes and objects to manage quiz data efficiently. Some core concepts of OOP used in this project include:  
- **Encapsulation:** The question data and logic are stored within dedicated classes (`Question`, `QuizBrain`), keeping the internal workings hidden from the main execution logic.  
- **Abstraction:** The quiz logic is abstracted away inside the `QuizBrain` class, making it easier to manage quiz flow without exposing complex details to the user.  
- **Modular Design:** Each functionality is separated into different modules (`data.py`, `questions_model.py`, `quiz_brain.py`), improving code organization and reusability.  

### 📌 Dynamic Question Handling  
- The `data.py` module contains a set of quiz questions that can be modified or expanded without altering the quiz logic.  
- Each question is modeled as an instance of the `Question` class, making it easier to manage and retrieve data in an organized way.  

### 📌 Quiz Brain – Handling the Logic  
The `QuizBrain` class is the backbone of the quiz application, responsible for:  
✔️ Keeping track of the current question number.  
✔️ Checking if more questions are available.  
✔️ Evaluating user answers and updating scores accordingly.  
✔️ Providing user-friendly feedback on correct/incorrect answers.  

### 📌 User Interaction  
- The `main.py` script runs the quiz by pulling questions from the `QuizBrain` and interacting with the user via the console.  
- Users are prompted with a question and given multiple choices. Their responses are evaluated, and feedback is provided instantly.  
- The final score is displayed at the end of the quiz.  

## 🛠 Technologies Used  
- **Python:** The core programming language used for development.  
- **OOP Principles:** Implemented through class-based design.  
- **Data Handling:** Questions are stored in a structured format for easy access.  

## 🚀 How to Run the Project  
1. Clone the repository:  
   ```bash
   git clone https://github.com/juniorcoderr/The-Quiz-Project.git
   cd The-Quiz-Project
   ```  
2. Run the main script:  
   ```bash
   python main.py
   ```  
3. Answer the questions and see your final score!  

## 📌 Future Enhancements  
- Implementing a GUI version using Tkinter or PyQt.  
- Adding an API-based question-fetching system (e.g., Open Trivia API).  
- Storing user scores for a leaderboard feature.  

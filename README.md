I Personal Finance Assistant
This project is an AI-powered personal finance assistant designed to help users track their income, manage expenses, and receive intelligent recommendations for improving their financial health. The application is built with a unique architecture that separates the core logical reasoning (the "AI") from the user interface.

The logical backend is implemented in Prolog, a declarative programming language that excels at solving problems based on rules and facts. The user-facing component is a dynamic single-page application built with HTML, Tailwind CSS, and JavaScript.

The project is structured to be easy to understand and extend, making it a great starting point for exploring the intersection of AI, logic programming, and web development.

Features
Dynamic Dashboard: View a real-time summary of your total income, total expenses, and net income.
Transaction Tracking: Easily add and categorize income and expense records.
Budgeting System: Set specific budgets for expense categories and receive an alert if your spending exceeds the limit.
Intelligent Recommendations: The AI provides actionable advice based on your financial data, including:
General financial health assessment.
Alerts for any single expense that makes up a significant portion of your total spending.
Specific guidance on managing "other" expenses when they exceed a reasonable threshold, suggesting strategies like better categorization and a temporary spending limit.
Data Persistence: Your financial data is saved locally in the browser, so it will be available the next time you open the application.
Reset Functionality: A built-in reset button allows you to clear all saved data and start fresh.
Technology Stack
Backend (Logical Core): The core AI logic is written in Prolog. The provided .pl file contains the facts and rules that power the financial analysis.
Frontend (User Interface): A single, self-contained HTML file. It uses native JavaScript to handle all front-end logic and Tailwind CSS for a clean, modern, and responsive design.
How to Run
This project demonstrates a conceptual full-stack application. To run the two main components:

Open the UI: Simply open the index.html file in any modern web browser. The UI is fully functional and uses a JavaScript class to simulate the Prolog logic.
Explore the Logic: To interact with the actual AI logic, you will need a Prolog interpreter (like SWI-Prolog). Load the prolog_logic.pl file and run queries directly in the console.
Note: For a real-world application, a server-side bridge (e.g., a Python script with the Pyswip library) would be required to connect the JavaScript frontend with the Prolog backend, enabling seamless, real-time communication.

Future Enhancements
Build a Python backend using a framework like Flask and the Pyswip library to create a working connection between the UI and Prolog.
Implement more sophisticated AI rules for long-term financial planning, savings goal tracking, and investment advice.
Add user authentication and a real database (like Firestore) to support multiple users and provide cloud-based data storage.
Enhance the UI with charts and graphs for a more visual representation of financial data.
Feel free to fork the repository and contribute!

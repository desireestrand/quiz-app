# Geekqwizz
A retro-themed quiz application built as a Single Page Application (SPA). The project focuses on mastering JavaScript's ability to manipulate the DOM dynamically and manage complex application states, timers, and animations without page reloads. Developed as a collaborative group project.

[Live Demo](https://desireestrand.github.io/quiz-app/)

---

### Features
* **Dynamic Category Selection:** Users can choose between 'Coding' and 'Gaming', triggering a real-time filter of the question data.
* **Shuffled Questions:** A shuffle algorithm randomizes the answer order for every question to ensure replayability and fairness.
* **Timed Challenges:** A 20-second countdown timer for each question to increase engagement and difficulty.
* **Instant Feedback & Animations:** Immediate visual feedback on answers combined with custom CSS transitions (fade-in/fade-out) for smooth state changes.
* **Persistent High Scores:** Integration with the Local Storage API to track and save the user's personal "Max Score" over time.
* **Responsive Design:** A mobile-first approach ensuring a seamless experience across all devices.

### Technical Implementation
The core of Geekqwizz is a custom-built rendering engine in Vanilla JS. Key technical highlights include:
* **Dynamic Rendering:** Instead of static HTML, the app utilizes document.createElement and replaceChildren to reconstruct the UI dynamically for a true SPA feel.
* **Filtering Engine:** I architected the category selection logic, ensuring the application remains scalable and can handle additional categories with minimal code changes.
* **Scoring System:** Built a logic-driven scoring system that compares current session performance against stored localStorage data, triggering unique feedback upon setting a new record.
* **Interval Management:** Implemented precise control over the Event Loop by managing and clearing intervals to prevent memory leaks and overlapping timers.

### Tech Stack
* **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3
* **Storage:** LocalStorage API
* **Architecture:** SPA (Single Page Application) principles
* **Collaboration:** Git-flow, GitHub, Agile (SCRUM, Kanban)

### Project Methodology
* **Agile Workflow:** Developed as a group project with a focus on collaborative problem-solving and task delegation.

### Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/desireestrand/quiz-app.git

2. Open the project:

    Open index.html in your preferred browser or use a Live Server extension.

Developed by Desirée Strand and team.

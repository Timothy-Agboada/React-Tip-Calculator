## 🚀 30-Day Coding Challenge: Day 23

This project is the twenty-third entry in my 30-day coding challenge. Today's goal was to build a practical, real-world utility application - a tip calculator - to practice handling multiple controlled inputs and performing real-time calculations in React.

### 📖 Project Overview

This is a modern and intuitive tip calculator built with React and styled with Tailwind CSS. The application allows users to input a bill amount, select a tip percentage from a predefined list, and specify the number of people to split the bill between. It instantly calculates and displays the tip amount per person and the total amount per person. A reset button is also included to easily clear the inputs.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jul-01-2025 18-21-10](https://github.com/user-attachments/assets/c8322a6f-8831-4c22-a8f0-79b64888b7da)


### 🌟 Key Features

* **Real-Time Calculations:** The tip and total amounts per person update instantly as the user modifies any of the inputs.
* **Component-Based Architecture:** The UI is broken down into reusable components (`InputBill`, `SelectTip`, `InputPeople`, `OutputDisplay`) for a clean and maintainable codebase.
* **Multiple Controlled Inputs:** The application effectively manages state for various input types, including number inputs and a custom button group for tip selection.
* **Intuitive Two-Column Layout:** A clean, responsive layout separates the input controls from the calculated results, making the app easy to use.
* **Reset Functionality:** A "Reset" button allows the user to clear all inputs and start a new calculation with a single click.
* **Modern & Accessible UI:** Styled with a fresh color palette and clear typography for a pleasant user experience.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface and managing state.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling and layout.
* **Font Awesome:** For icons in the input fields.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-tip-calculator.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-tip-calculator
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a practical exercise in several key React concepts:

* **Managing Multiple State Variables:** Using the `useState` hook to handle several independent pieces of state within a single component.
* **Component Communication:** Passing state values and setter functions down as props to child components, allowing them to be controlled by their parent.
* **Derived State:** Reinforcing the concept of calculating display values from base state on every render, rather than storing those calculated values in state themselves.
* **Building Controlled Forms:** Gaining more experience with the standard React pattern for building interactive forms.
* **Conditional Logic in Rendering:** Disabling the reset button based on the current state to improve the user experience.

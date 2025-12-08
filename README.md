
# 🎓Dent_GPA - CGPA Calculator + Honours Tracker

A Simple CGPA Calculator and Honours tracker designed for BDS students of **University of Peradeniya**.

> **Live Demo:** [Click here to use the Calculator](https://d20043-sketch.github.io/Dent_GPA/)

<!-- ![App Screenshot](https://via.placeholder.com/800x400?text=App+Screenshot+Here)
*(Add a screenshot of your app here later!)* -->

## 🚀 Key Features

* **⚡ Instant Calculation:** Calculates CGPA in real-time based on the specific credit structure of the degree.
* **🎯 Honours Forecasting:** Tells you exactly what average GPA you need in future semesters to achieve a **First Class**, **Second Upper**, etc.
* **🌙 Smart Dark Mode:** Automatically detects system preferences and remembers your choice.
* **🔒 Privacy Focused:** No database. All data is stored locally on your device. Your results never leave your phone.
* **📱 Mobile First:** Optimized design for usage on smartphones.

## 🛠️ How It Works

1.  **Select Semester:** Choose which semester you are currently in.
2.  **Input Semester GPA:** Enter the GPA for your completed semesters.
3.  **View Forecast:** The app calculates your current standing and projects the required average for remaining semesters.
    * ✅ **On Track:** You are safe to maintain current performance.
    * ❌ **Non attainable:** The goal is mathematically unreachable (requires > 4.0).

## ⚙️ Configuration (For Developers)

This project is built as a **Single Page Application (SPA)** using vanilla HTML, CSS, and JavaScript. It is designed to be easily adaptable for other degree programmes that have predefined course systems like BDS degree programme. 

To adapt this for your own university:

1.  Open `index.html`.
2.  Locate the `CONFIGURATION` section in the JavaScript.
3.  Update the **Credit Map**:
    ```javascript
    const semesterData = [
        { id: 1, name: "1st Semester", credits: 14 },
        // ... update credits here
    ];
    ```
4.  Update the **Honors Cutoffs**:
    ```javascript
    const honorsGoals = [
        { name: "First Class", minCGPA: 3.70 },
        // ... update cutoffs here
    ];
    ```

## 💻 Tech Stack

* **Frontend:** HTML5, CSS3 and JavaScript 
* **Icons:** Inline SVGs (No external requests).
* **Fonts:** Google Fonts (Inter).

## 🏃‍♂️ Running Locally

To run this project on your machine:

1.  Clone the repository:
    ```bash
    git clone https://github.com/d20043-sketch/Dent_GPA.git
    ```
2.  Navigate to the folder:
    ```bash
    cd Dent_GPA
    ```
3.  Open `index.html` in any web browser.

## 📄 Disclaimer

This tool is for planning purposes only. Please refer to the official University of Peradeniya transcripts for verified academic results.

---

Developed by **Ramanitharan Kanishkar**.

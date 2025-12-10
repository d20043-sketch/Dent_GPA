
# 🎓 Dent_GPA - CGPA Calculator + Honours tracker

A simple CGPA Calculator and Honours tracker designed for BDS students of **University of Peradeniya**.

> **Live Demo:** [Click here to use the Calculator](https://d20043-sketch.github.io/Dent_GPA/)

<!-- ![App Screenshot](https://via.placeholder.com/800x400?text=App+Screenshot+Here)
*(Add a screenshot of your app here later!)* -->

## 🚀 Key Features
* **Run Locally:** The application is a single HTML file and runs instantly from any device's local storage—just open the file!
* **Instant Calculation:** Calculates CGPA in real-time.
* **Visual Progress Tracking:** Animated progress bar shows your degree completion percentage 
* **Smart Input Validation:** Color-coded inputs with real-time feedback
* **Honours Forecasting:** Tells exact average GPA you need in future semesters to achieve a **First Class**, **Second Upper**, etc.
* **Smart Dark Mode:** Automatically detects system preferences and remembers your choice.
* **Privacy Focused:** No database. All data is stored locally on your device.
* **Mobile First:** Optimised design for usage on smartphones.
* **Auto-Restore Data:** All previously entered semester results remain on your device and are automatically restored each time you reopen the calculator.

## 🛠️ How It Works

1.  **Select Completed Semesters:** Choose how many semesters you have completed.
2.  **Input Semester GPAs:** Enter the GPA for each completed semester.
3.  **View Results:** The app calculates your current CGPA. 
4.  **View Honours Forecast:** See what average GPA you need in remaining semesters to achieve First Class, Second Upper, etc.
    * ✅ **On Track:** You can maintain current performance.
    * ❌ **Unattainable:** The goal is mathematically unreachable (requires > 4.0).
    * **Specific GPA Required:** Shows the exact average needed in upcoming semesters.

## ⚙️ Configuration (For Developers)

This project is built as a **Single Page Application (SPA)** using vanilla HTML, CSS, and JavaScript. It is designed to be easily adaptable for other degree programmes that have predefined course systems like BDS degree programme. 

To adapt this for your own university:

1.  Open `index.html`.
2.  Locate the `// ============ DATA STRUCTURES ============` section in the JavaScript (around line 630).
3.  Update the **Credit Map**:
    ```javascript
    const semesterData = [
        { id: 1, name: "1st Semester GPA", credits: 14 },
        // ... update credits here
    ];
    ```
4.  Update the **Honours Cutoffs**:
    ```javascript
    const honorsGoals = [
        { name: "First Class", minCGPA: 3.70 },
        // ... update cutoffs here
    ];
    ```

## 💻 Tech Stack

* **Frontend:** HTML5, CSS3 and JavaScript 
* **Icons:** Unicode emojis


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

# 🎮 Genre-Based Game Discovery Platform

This is a simple web application that predicts the **genre of a video game** based on its name.
It is built using **Python Flask** and basic **HTML templates**.

This project is ideal for beginners to understand:

* How web apps work
* How frontend connects with backend
* How user input is processed

---

## 🚀 What This Project Does

1. User enters a game name (like "FIFA" or "Call of Duty")
2. The app processes the input
3. It checks predefined rules
4. It displays the predicted genre

---

## 🛠️ Technologies Used

* Python
* Flask (Web framework)
* HTML (Frontend templates)

---

## 📂 Project Structure

Make sure your folder looks like this:

project-folder/

│── app.py
│── requirements.txt
│── templates/
│     ├── index.html
│     └── result.html

---

## ⚙️ STEP-BY-STEP SETUP GUIDE (VERY IMPORTANT)

### 🔹 Step 1: Install Python

* Download Python from: https://www.python.org/downloads/
* While installing, make sure you check:
  ✔ "Add Python to PATH"

---

### 🔹 Step 2: Create Project Folder

Create a new folder anywhere (Desktop recommended):

Example:
game-genre-app

---

### 🔹 Step 3: Add Files

Inside the folder, create:

1. app.py
2. requirements.txt
3. A folder called **templates**
4. Inside templates, create:

   * index.html
   * result.html

---

### 🔹 Step 4: Install Dependencies

Open terminal / command prompt inside your project folder and run:

pip install -r requirements.txt

This installs Flask.

---

### 🔹 Step 5: Run the Application

Run this command:

python app.py

---

### 🔹 Step 6: Open in Browser

Go to:

http://127.0.0.1:5000/

---

### 🔹 Step 7: Test the App

Try entering:

* Call of Duty → Shooter
* FIFA → Sports
* Elden Ring → RPG
* Forza → Racing

---

## 🧠 How the Logic Works (VERY SIMPLE)

The backend has a function:

* Converts input to lowercase
* Checks keywords using if-else conditions
* Returns a genre

Example:

if "fifa" in game_name → Sports
if "elden ring" → RPG

---

## 📄 File Explanation

### 🔹 app.py

* Main backend file
* Handles routing and logic

### 🔹 index.html

* Takes user input

### 🔹 result.html

* Displays result

### 🔹 requirements.txt

* Contains Flask dependency

---

## 🔍 Example Output

Input: Elden Ring
Output: RPG

---

## 📌 Future Improvements

* Use Machine Learning instead of rules
* Add game database
* Improve UI with CSS
* Add multiple recommendations

---

## 👨‍💻 Author

Your Name

---

## 📄 License

Open-source (MIT License)

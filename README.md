# SmartStudyPlanner

SmartStudyPlanner is a **rule-based, energy-aware study planning web application** that helps students create **realistic and burnout-free study schedules**.  
Instead of idealistic to-do lists, it intelligently plans study sessions by considering **energy levels, subject difficulty, and mental fatigue**.

---

## 🎯 Problem It Solves

Many students overplan their study schedules without accounting for:
- fluctuating energy levels,
- subject difficulty,
- cognitive fatigue.

This often leads to burnout or incomplete plans.

**SmartStudyPlanner fixes this** by generating study schedules that are **practical, balanced, and sustainable**.

---

## 🚀 Demo

**Screenshots of the planner in action:**

<img width="637" height="628" alt="SmartStudyPlanner UI" src="https://github.com/user-attachments/assets/941915d6-afdb-41dd-9148-8937a57306c9" />

<img width="637" height="628" alt="Generated Study Plan" src="https://github.com/user-attachments/assets/c399ffe3-34e7-437c-842d-128e97a94d20" />

---

## ✨ Key Features

- **Energy-aware planning**  
  Adjusts study session difficulty based on the user’s current energy level (low / medium / high).

- **Difficulty-based subject ordering**  
  Schedules harder subjects during high-energy periods and easier ones during low-energy periods.

- **Burnout prevention logic**  
  Prevents back-to-back hard subjects by rotating difficulty levels.

- **Smart breaks**  
  Automatically inserts breaks based on study intensity and continuous focus time.

- **Transparent decision-making**  
  Each session explains *why* it was scheduled at that point (e.g., energy level + difficulty).

- **Realism checks & warnings**  
  Alerts the user when a study plan is unrealistic and suggests a more achievable approach.

---

## 🧠 How It Works (Logic Overview)

1. The user provides:
   - Total available study hours  
   - Current energy level  
   - Subjects with difficulty ratings  

2. The planner:
   - Filters subjects based on energy level.
   - Divides time into 45-minute focused study blocks.
   - Avoids scheduling two hard subjects consecutively.
   - Inserts breaks dynamically based on fatigue rules.

3. Each session includes a short explanation describing:
   - why it was placed at that time,
   - how it supports focus and prevents burnout.

4. If constraints conflict (e.g., low energy + many hard subjects), the app displays a warning.

---

## 🛠 Tech Stack

- **HTML** – Structure and layout  
- **CSS** – Clean, minimal UI styling  
- **JavaScript** – Core logic, rule-based scheduling, and state management  

✔ Runs completely in the browser  
✔ No installation or backend required

---

## ▶️ How to Use

1. Open `index.html` in your browser.
2. Enter total study hours.
3. Select your current energy level.
4. Add subjects with difficulty levels.
5. Click **Generate Plan** to view your personalized study schedule.

---

## 🔮 Future Improvements

- Adaptive feedback loop to refine session length over time.
- Visual energy curve to show focus vs fatigue.
- Day-pattern presets (morning person / night owl).
- Mobile responsiveness and improved accessibility.

---

## 📌 Why This Project Matters

This project demonstrates:
- logical thinking and rule-based system design,
- real-world problem solving,
- clean UI + functional JavaScript integration.

It goes beyond basic to-do or Pomodoro apps by focusing on **realistic human behavior and mental energy**.

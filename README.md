# SmartStudyPlanner

A rule-based smart study planner that generates energy-aware, difficulty-balanced study schedules to prevent overplanning and burnout.

---

## Features

- Energy-aware planning: Schedules subjects based on user’s current energy level (low/medium/high).
- Difficulty-based ordering: Hard subjects appear when energy is high, easier subjects when energy is low.
- No back-to-back hard subjects to prevent burnout.
- Automatic breaks depending on difficulty and study intensity.
- “Why this session?” explanation for each scheduled session.
- Warnings if the plan is unrealistic (e.g., too many hard subjects with low energy).

---

## How it Works

1. User enters:
   - Total study hours
   - Energy level (low/medium/high)
   - Subjects with difficulty ratings
2. The planner filters subjects based on energy.
3. Generates 45-minute study sessions:
   - Rotates subjects to avoid consecutive hard sessions.
   - Inserts breaks automatically.
4. Each session shows a short explanation of **why it was placed there**.
5. If the plan is unrealistic, a warning is shown and suggestions are provided.

---

## Tech Stack

- HTML
- CSS
- JavaScript
- Runs entirely in the browser (no installation required)

---

## Usage

1. Open `index.html` in a browser.
2. Add your subjects and difficulties.
3. Select your energy level and total study hours.
4. Click “Generate Plan” to view your personalized study schedule.

---

## Future Improvements

- Add feedback loop to adjust session lengths dynamically.
- Visualize energy curve throughout the day.
- Add day-pattern presets (morning person/night owl).
- Make it mobile-responsive.

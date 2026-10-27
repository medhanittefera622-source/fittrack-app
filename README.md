# 🏋️‍♂️ FitTrack - Daily Workout & Goal Progress Logger

FitTrack is a full-stack web application designed to help users record daily workouts, track sets/reps, and monitor fitness progress over time.

## 🛠️ Built With
- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Security:** bcrypt, JSON Web Tokens (JWT)
## 🗄️ Database Architecture
- **`users`**: Manages user accounts and authentication state.
- **`workouts`**: Tracks session titles, dates, and notes (linked to `users`).
- **`exercises`**: Records sets, reps, and weight per movement (linked to `workouts`).
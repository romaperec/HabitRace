# Habit Race 🚀

**Habit Race** is a social habit-tracking app that transforms building habits into an exciting competition. Create habits, invite friends, and compete to see who can stick to their goals the longest. Track your progress, climb the leaderboard, and stay motivated to achieve new milestones every day!

---

## 🌟 Features

- **Create and Manage Habits**: Easily add, edit, and delete daily habits.  
- **Compete with Friends**: Invite friends and challenge them to stick to their goals.  
- **Track Progress**: Visualize your habit streaks and consistency over time.  
- **Leaderboards & Achievements**: Compete for the top spot and earn achievements.  
- **Secure Authentication**: Utilize JWT for secure user login.  

---

## ⚙️ Installation

1. **Clone the repository**:

```bash
git clone https://github.com/romaperec/HabitRace.git
cd HabitRace
```

2. **Install dependencies**:

```bash
uv pip install -r requirements.txt
```

3. **Run the server**:

```bash
uvicorn src.main:app --reload
```

---

## 🛠 Tech Stack

- **Python 3.13**  
- **FastAPI** for building the API  
- **SQLAlchemy** for ORM and database management  
- **SQLite** as the database  
- **Ruff** for code linting  
- **Pytest** for testing  

---

## 🚀 Development Commands

- **Format code**:

```bash
ruff check . --fix
```

- **Run tests**:

```bash
pytest
```

---

## 📄 API Documentation

Once the server is running, access the API docs at:

- Swagger UI: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)  
- ReDoc: [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)  

---

## 🔥 Future Plans

- Develop a mobile version  
- Add advanced challenges for competitive users  
- Create a reward system with badges and achievements  
- Introduce social features like comments and progress sharing  

---

## 🤝 Contribution

1. Fork the repository  
2. Create a new branch: `git checkout -b feature/my-feature`  
3. Commit your changes: `git commit -m "Add some feature"`  
4. Push to the branch: `git push origin feature/my-feature`  
5. Open a Pull Request  

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

> **Habit Race** — Stay motivated and build better habits every day! 💪🔥


# Simple-Budgeting-
A simple budgeting app built just for clarity
# Simple Budget App

A minimal Flask web app for tracking monthly income, savings goals, and spending caps per category (e.g. rent, food, transport, gym, subscriptions).

## Features

- Set monthly income and savings goal.
- Define spending caps for each category.
- Add expenses and see real‑time progress bars per category.
- Track total spent and remaining budget.

## How to run locally

1. Install Python 3.8+ and pip.
2. Install dependencies:
   ```bash
   pip install flask gunicorn
   ```
3. Run:
   ```bash
   python app.py
   ```
4. Open your browser and go to `http://localhost:5000`.

## Deployment (optional)

You can host this on platforms like:
- **Railway** (free tier for small apps).
- **Render** (free tier for hobby apps).

Steps:
1. Push this repo to GitHub.
2. Create a new project on Railway/Render and link your GitHub repo.
3. Set the runtime to **Python** and start command to:
   ```bash
   gunicorn app:app
   ```
4. Your app will be available at a public URL.

## License

This project is licensed under the [MIT License](LICENSE).

# Expense_Tracker
---

# L7 Informatics

A Python command-line application that enables users to efficiently track their daily expenses, manage monthly budgets, and monitor their savings goals. The app features budget alerts, category-wise tracking, and supports Docker for simplified deployment.

---

## 🚀 Features

- Log daily expenses with category and description
- Set monthly budgets per category
- Track total monthly expenses
- Compare spending vs. budget per category
- Alert when budget limit is crossed
- JSON-based data persistence

### 🏅 Bonus Features Implemented

- Different budgets per month
- Docker support for containerized execution

---

## 🗂️ Project Structure

```
Expense_Tracker/
├── README.md
├── expense_tracker.py             # Core application logic
└── Dockerfile             # Docker container setup
```

---

## Steps for implementation

### 1. Clone the Repository
```bash
git clone https://github.com/Murari-10/Expense_Tracker.git
cd Expense_Tracker
```

### 2. Install the Python and the Docker

install the python 3.8 which is suitable.

### 3. Run the Application

python expense_tracker.py

### 4.Docker Usage

1. Bulid the Docker Image
   ```bash
   docker build -t expense-tracker .
   ```
3. Run the Container
   ```bash
   docker run -it --rm expense-tracker
   ```


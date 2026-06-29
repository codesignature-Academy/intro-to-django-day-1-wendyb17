[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8hRnlSwV)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=24191476&assignment_repo_type=AssignmentRepo)
# Django Assignment 1: Creating Your First Django Project

## Objective

In this assignment, you will:

* Create and activate a Python virtual environment.
* Install Django.
* Create a Django project named **todo_project**.
* Run the Django development server.
* Understand the purpose of key Django project files.
* Commit and submit your work through **GitHub Classroom**.

---

## Instructions

### Task 1: Clone Your GitHub Classroom Repository

1. Accept the GitHub Classroom assignment.
2. Clone your repository to your computer.

```bash
git clone <your-classroom-repository-url>
```

3. Navigate into the project folder.

```bash
cd <repository-name>
```

---

### Task 2: Create a Virtual Environment

Create a virtual environment named **venv**.

**Windows**

```bash
python -m venv venv
```

**Linux/macOS**

```bash
python3 -m venv venv
```

Activate it.

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

---

### Task 3: Install Django

Install Django.

```bash
pip install django
```

Verify the installation.

```bash
django-admin --version
```

---

### Task 4: Create the Django Project

Create a Django project named:

```text
todo_project
```

Use:

```bash
django-admin startproject todo_project .
```

---

### Task 5: Run the Development Server

Start the development server.

```bash
python manage.py runserver
```

Open:

```
http://127.0.0.1:8000/
```

You should see Django's default welcome page.

---

### Task 6: Understand the Project Files

Open the following files:

* `manage.py`
* `todo_project/settings.py`
* `todo_project/urls.py`

Create a file named:

```
answers.md
```

Inside **answers.md**, write **one sentence** explaining the purpose of each file.

Example:

```markdown
# Django Assignment Answers

## Question 1

### manage.py
Your explanation here.

### settings.py
Your explanation here.

### urls.py
Your explanation here.
```

Write the explanations in your own words.

---

## Submission Instructions

After completing the assignment:

### 1. Check your files

```bash
git status
```

### 2. Stage your changes

```bash
git add .
```

### 3. Commit your work

```bash
git commit -m "Complete Django Assignment 1"
```

### 4. Push to GitHub Classroom

```bash
git push origin main
```

> If your default branch is `master`, use:

```bash
git push origin master
```

---

## Repository Checklist

Before submitting, your repository should contain:

* `manage.py`
* `todo_project/`
* `answers.md`
* `requirements.txt`

Generate `requirements.txt` with:

```bash
pip freeze > requirements.txt
```

---

## Grading Rubric

| Task                                                   |         Marks |
| ------------------------------------------------------ | ------------: |
| Virtual environment created                            |            10 |
| Django installed                                       |            15 |
| Django project created                                 |            20 |
| Development server runs successfully                   |            20 |
| Correct explanations in `answers.md`                   |            20 |
| `requirements.txt` included                            |             5 |
| Git commits and successful GitHub Classroom submission |            10 |
| **Total**                                              | **100 Marks** |

## Notes

* Do **not** upload the `venv` folder.
* Ensure your repository contains a `.gitignore` file that excludes the virtual environment and Python cache files.
* Push your final commit before the assignment deadline. Only the latest commit on GitHub Classroom will be graded.

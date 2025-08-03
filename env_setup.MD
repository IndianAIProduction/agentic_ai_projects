
# 🛠️ Course Setup: Python Virtual Environment with `virtualenv`

Welcome to the course! Before we start coding, it’s important to set up your Python environment properly. This ensures all your dependencies are managed and your project remains clean and conflict-free.

---

## 📦 Step 1: Install `virtualenv`

First, install the `virtualenv` package using `pip`.

```bash
pip install virtualenv
```

✅ **Check if installed correctly:**

```bash
virtualenv --version
```

If you see a version number, it's installed successfully.

---

## 📁 Step 2: Navigate to Your Project Folder

Open a terminal and navigate to the folder where you want to keep your project.

```bash
cd <path-to-your-project-folder>
```

Replace `<path-to-your-project-folder>` with the actual folder path.

---

## 🧪 Step 3: Create a Virtual Environment

Create a virtual environment inside your project directory:

```bash
virtualenv .\<environment-name>
```

📌 Example:

```bash
virtualenv .\venv
```

This will create a new folder called `venv` inside your project directory.

---

## 🚀 Step 4: Activate the Environment

### ✅ On Windows

```bash
.\venv\Scripts\activate
```

Once activated, your terminal prompt will look something like:

```
(venv) C:\Users\YourName\YourProjectFolder>
```

This means you are now working inside the virtual environment.

---

## 🐍 Step 5: Run Python Inside the Environment

To start the Python interpreter:

```bash
python
```

You should see something like:

```
Python 3.x.x (default, ...) on win32
>>>
```

Try running a Python command:

```python
print("Hello, world!")
```

To exit the interpreter:

```python
exit()
```

---

## ❌ Step 6: Deactivate the Environment

Once you’re done working in the virtual environment, you can deactivate it with:

```bash
deactivate
```

This returns your terminal to the system's global Python environment.

---

## 📋 Quick Summary

| Task                    | Command                                  |
|-------------------------|-------------------------------------------|
| Install virtualenv      | `pip install virtualenv`                 |
| Check version           | `virtualenv --version`                   |
| Navigate to folder      | `cd <your-folder-path>`                  |
| Create environment      | `virtualenv .\venv`                      |
| Activate environment    | `.\venv\Scripts\activate`             |
| Start Python            | `python`                                 |
| Exit Python             | `exit()`                                 |
| Deactivate environment  | `deactivate`                             |

---

🎉 That’s it! You’re now ready to begin coding in a clean, isolated Python environment.

Happy learning! 🚀

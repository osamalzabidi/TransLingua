# Contributing Guide

Thank you for your interest in contributing to **TransLingua Desktop**!
We welcome improvements, bug fixes, new features, and documentation updates.

---

## 🧱 Contribution Requirements

### **1. Python Version**
All contributions **must use Python 3.12+**.  
Older versions are not supported for development.

### **2. Code Style**
We enforce a strict formatting style using:

- **Black** (auto‑formatter)  
- **isort** (import sorter)  
- **pylance** (optional: linting)

Before pushing your code, run:

```bash
black .
isort .
```

---

## 🔧 Development Setup

### **Clone the repository**
```bash
git clone https://github.com/osamalzabidi/TransLingua.git
cd TransLingua
```

### **Create a virtual environment**
```bash
python3 -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate    # Windows
```

### **Install dependencies**
```bash
pip install -r requirements.txt
```

---

## 🧪 Testing

Before opening a pull request, ensure the application runs correctly:

```bash
python main.py
```

If you are adding new helper functions or translation logic, include small test cases where possible.

---

## 🌿 Branching Strategy

- **main** → stable releases  
- **dev** → active development  
- Feature branches should be named like:
  ```
  feature/your-feature-name
  bugfix/fix-description
  docs/update-readme
  ```

---

## 📬 Submitting a Pull Request

Ensure your PR includes:

1. A clear explanation of the change
2. Screenshots if UI was modified
3. Confirmation that formatting has been applied
4. Confirmation that Python 3.12+ was used
5. Minimal and clean commit history

---

## 🧩 Areas Where Help is Needed

- Voice recognition improvements
- Camera OCR module
- Translation engine extensibility

---

## ❤️ Code of Conduct

Be respectful. Write clean code. Help others.
We're building a great translation tool together.

---

## 📄 License

By contributing, you agree that your contributions will be licensed under the **GPL-3.0 License**.


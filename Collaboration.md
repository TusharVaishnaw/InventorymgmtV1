# 👥 Inventory Management Team Git Workflow

Welcome to the Inventory Management System project!
This document explains exactly how our team will collaborate using Git and GitHub.

---

## 📌 Branching Structure

* **main** → Production-ready code only
* **dev** → Active development, integration of features
* **feature/<your-feature-name>** → One branch per task/person

---

## 🧑‍✈️ For Tushar (Repo Owner)

### Create the `dev` Branch (Run in Terminal inside project folder):

```bash
git checkout main
git pull origin main
git checkout -b dev
git push -u origin dev
```

---

## 👥 For Team Members

### 🛠️ One-Time Setup

```bash
git clone https://github.com/TusharVaishnaw/InventorymgmtV1.git
cd InventorymgmtV1
git fetch --all
git checkout dev
git pull origin dev
```

---

## ✅ Simple Git Workflow (Feature-first, Push-last)

### 1. Switch to `dev` and get the latest updates

```bash
git checkout dev
git pull origin dev
```

### 2. Create a new feature branch

```bash
git checkout -b feature/<your-feature-name>
```

### 3. Do all your work and test it **locally**

* Don't push anything yet
* Finish the feature completely first

### 4. When the feature is 100% ready:

```bash
git add .
git commit -m "Complete: <feature-name> ✅"
git push -u origin feature/<your-feature-name>
```

Then, go to GitHub and **create a Pull Request from your feature branch to `dev`**.

---

## 🚫 Don't Do This

* ❌ Don’t push half-done work
* ❌ Don’t work directly on `main` or `dev`
* ❌ Don’t make random commits during a task

---

## 🧠 Need Help?

Use GPT.

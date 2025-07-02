# 👥 Inventory Management Team Git Workflow

Welcome to the Inventory Management System project!
This document explains exactly how our team will collaborate using Git and GitHub.

---

## 📌 Branching Structure

* **main** → Production-ready code only
* **dev** → Active development, integration of features
* **feature/<your-feature-name>** → One branch per task/person

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

This will just clone the latest finalised code into your system.
```bash
git checkout dev
git pull origin dev
```
DO NOT COMMIT OR PUSH ONTO THIS BRANCH.

### 2. Create a new feature branch
For anything finalised feature you have added create a new branch like this and push to it.
```bash
git checkout -b feature/<your-feature-name>
```
I'll review and test the code and pull request to the dev branch.

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

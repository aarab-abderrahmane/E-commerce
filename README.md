# ElectroZone – Frontend Project

This repository is dedicated to developing the ElectroZone website frontend (Home page for phase one).  
Each member works on a specific part of the design using a separate branch.

---

# 1. Download the Project

1. Open your terminal.
2. Run:
```bash
git clone https://github.com/USERNAME/REPO.git
```
3. Enter the directory:
```bash
cd REPO
```
4. Install dependencies:
```bash
npm install
```
5. Start the project:
```bash
npm run dev
```

---

# 2. Working With Branches

Do not modify the **main** branch directly.  
Each member must work on their own branch.

### Create your branch:
```bash
git checkout -b feature/your-branch-name
```

Example:
```bash
git checkout -b feature/navbar
```

### Keep your project updated:
```bash
git pull origin main
```

---

# 3. Start Working on Your Section

1. Switch to your branch:
```bash
git checkout feature/your-branch-name
```
2. Edit only the files related to your assigned component.
3. Do not modify files outside your task.

---

## **Essential Tools**

1. **React.js** ✅  
   This project is built using React. You need to be familiar with basic React concepts to contribute effectively.

2. **Tailwind CSS** ✅  
   Tailwind is required for styling in this project. All final components should follow Tailwind conventions.

---

## **Notes for Beginners**

* You **can use plain CSS** while testing your code and building components.  
* Once your code works correctly, you **should convert the styling to Tailwind CSS** before submitting your changes.  
* This helps maintain consistency across the project while allowing beginners to experiment freely.

---

# 4. Save and Upload Your Work (Commit + Push)

After making your changes:
```bash
git add .
git commit -m "Your message"
git push origin feature/your-branch-name
```

Example:
```bash
git push origin feature/navbar
```

---

# 5. Submit Your Work for Review (Pull Request)

After pushing:

1. Open the GitHub repository.
2. Click **Compare & Pull Request**.
3. Add a clear title, such as:
```
Navbar Component Completed
```
4. Submit the PR.

The team lead will review and merge into **main**.

---

# 6. Update Your Branch Daily

Before working each day:
```bash
git checkout main
git pull origin main
git checkout feature/your-branch-name
git merge main
```

---

# 7. Using Trello

Trello is used to organize tasks.

### Board lists:
* To Do  
* In Progress  
* Review  
* Done

### Workflow:
1. Move your task from **To Do** → **In Progress** when you start.
2. After creating a PR, move it to **Review**.
3. Once approved, it will be moved to **Done**.

---

# 8. Rules

* Do not work on another member’s branch.
* Do not modify the main branch directly.
* All work must go through branches + pull requests.
* Always update your branch before working.
* Use clear commit messages.



---

# 9. Support

If you encounter any issues:
* Add them to the Trello “Problems” section  
* Or contact the team lead on Discord



# 🛠️ Guide: How to Fix a Mistake if You Edited a File Not Related to Your Task

If you accidentally added changes to files that are not part of your task, follow these steps to fix the situation without affecting the project:

---

## 1️⃣ Check the branch you are working on

Make sure you are on **your own branch only**:

```bash
git checkout feature/your-branch
````

---

## 2️⃣ Restore the original file from main

Replace the modified file with the original version from main:

```bash
git checkout main -- path/to/file
```

> Example:

```bash
git checkout main -- src/components/Footer.jsx
```

---

## 3️⃣ Save the changes and push

```bash
git add .
git commit -m "fix: removed unintended changes"
git push origin feature/your-branch
```

---

## 4️⃣ Verify on GitHub

* Open your Pull Request.
* Make sure no other files were changed.
* Now only the files related to your task remain, ready for review.

---

## ⚠️ Important Tips

* **Never make changes directly on the main branch.**
* All edits should be made on your own branch only.
* Before any push, check the modified files using:

```bash
git status
```




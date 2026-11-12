# 🌟 Complete Guide: Transforming Your GitHub into a Professional Developer Portfolio

This package contains everything configured specifically for **Bijan Sarkar** (`bijan-sarkar`).

---

## 📁 What We Built For You

- **`README.md`**: Modern profile markdown featuring dynamic typing animations, categorized tech badges, live GitHub analytics cards, contribution snake display, featured projects table, and social links.
- **`.github/workflows/snake.yml`**: GitHub Actions automated workflow that updates your contribution snake game daily.

---

## 🚀 Step 1: Create the Special Profile Repository

GitHub has a feature where creating a public repository named exactly the same as your username displays its `README.md` directly on your main profile page.

1. Go to [github.com/new](https://github.com/new).
2. Set **Repository name** to: `bijan-sarkar`
3. Check **Public** (it must be Public to display on your profile).
4. Check **Add a README file**.
5. Click **Create repository**.

---

## 💻 Step 2: Push the Files to Your Profile Repository

You can copy and paste the contents of `README.md` directly via the GitHub web editor, or push these prepared files using Git:

```powershell
cd "C:\Users\Bijan\.gemini\antigravity\scratch\github-profile"
git init
git branch -M main
git remote add origin https://github.com/bijan-sarkar/bijan-sarkar.git
git add .
git commit -m "feat: setup professional profile and snake animation workflow"
git push -u origin main
```

*(If you already initialized the repo on GitHub with a README, do a `git pull origin main --rebase` before pushing, or replace the README.md content on GitHub.com directly).*

---

## ⚙️ Step 3: Enable the Contribution Snake Workflow

1. In your `bijan-sarkar/bijan-sarkar` repository on GitHub, navigate to **Settings** > **Actions** > **General**.
2. Scroll to **Workflow permissions**:
   - Select **Read and write permissions**.
   - Click **Save**.
3. Go to the **Actions** tab > Click **Generate Contribution Snake** on the left > Click **Run workflow** > **Run workflow**.
4. Once completed, it generates an `output` branch with your snake SVG animations that display automatically on your profile!

---

## 🎯 Step 4: Optimize Your Profile Sidebar & Metadata

Go to [github.com/settings/profile](https://github.com/settings/profile):

| Field | Recommended Value |
| :--- | :--- |
| **Name** | `Bijan Sarkar` |
| **Bio** | `CSE Student & Full-Stack Developer | Python, FastAPI, React/TS | Grinding DSA in C++ & Scalable Systems 🚀` |
| **Location** | `Dhaka, Bangladesh` (or your current location) |
| **Social accounts** | Add your LinkedIn (`https://linkedin.com/in/bijan-sarkar`), Portfolio, or Twitter |
| **Display private contributions** | Go to your public profile > Click **Contribution settings** (top right of graph) > Check **Private contributions** (turns your private repo commits into green squares!) |

---

## 📌 Step 5: Pin Your Top Repositories

On your public profile page, click **Customize your pins** and select your best 4 to 6 projects:
1. `DIU_semester-Tracker` (Academic Portal / Full-Stack)
2. `task-master-app` (Productivity & Dockerized Full-Stack)
3. `Pomoman` (Interactive Productivity Utility)
4. `CS50-python` (Algorithmic / Python Mastery)

### For each pinned repository:
- Add a 1-sentence **Description** under the repository's "About" section.
- Add **Topics** (e.g. `fastapi`, `react`, `typescript`, `docker`, `tailwindcss`, `python`).
- Add the **Website** URL if the project is hosted live (e.g. Render, Vercel).
- Add a clean `README.md` and an open-source license (MIT).

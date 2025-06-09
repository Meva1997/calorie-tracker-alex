# 🥗 Calorie Tracker Alex

**Calorie Tracker Alex** is a clean, responsive, and easy-to-use web app for tracking your daily calories—both consumed (food) and burned (exercise). Designed with React + TypeScript, powered by Vite and styled with TailwindCSS, this app helps you stay on top of your nutrition and fitness goals!

---

## 🚀 Features

- **Quick Logging:** Add food or exercise activities in seconds.
- **Live Calorie Summary:** Instantly see calories consumed, burned, and net total.
- **Persistent Data:** All your activities are stored locally—close and return anytime!
- **Intuitive Activity List:** Edit or delete any entry. Visual category highlighting.
- **Restart With One Click:** Wipe your activities and start fresh.
- **Modern Interface:** Built with TailwindCSS for a beautiful and mobile-friendly UI.
- **Fully Open Source:** Fork, modify, or contribute!

---

## 🖥️ Tech Stack

- **React** + **TypeScript**
- **Vite** (super-fast dev/build)
- **TailwindCSS** (utility-first styling)
- **ESLint** (with React/TypeScript plugin recommendations)
- **LocalStorage** (for data persistence)

---

## 🛠️ Getting Started

1. **Install Dependencies**
   ```bash
   npm install
   ```
2. **Start Development Server**
   ```bash
   npm run dev
   ```
3. **Build for Production**
   ```bash
   npm run build
   ```

---

## 📂 Project Structure

```plaintext
src/
  components/      # UI components (Form, CalorieTracker, ActivityList)
  context/         # React Context for global state
  reducers/        # State management logic
  data/            # Static data (categories)
  hooks/           # Custom React hooks
  types/           # TypeScript types
public/
index.html         # App entry point
```

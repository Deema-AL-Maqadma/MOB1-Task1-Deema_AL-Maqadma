# Mobile App Development 1 - Task 1 (UI Layouts)

**Course:** Mobile App Development 1 (ITNM3315)  
**Instructor:** Eng. Ibrahim O. I. Kaware  
**Student Name:** Deema AL-Maqadma  
**Institution:** Al-Aqsa University  
**Repository:** `MOB1-Task1-Deema_AL-Maqadma`

---

## 📌 Project Overview
This repository contains the practical implementation of **Module 1 (UI Layouts and Resources)** for Native Android using **Java** and **XML**. It demonstrates mastery of different Android layouts, view hierarchies, vector assets, and seamless **Light and Dark Mode** support.

---

## 🛠️ Tech Stack & Concepts
- **Language:** Java (Native Android SDK)
- **UI Design:** Declarative XML (ConstraintLayout, LinearLayout, RelativeLayout, ScrollView)
- **Theming:** Full Dual-Theme Architecture (`values/colors.xml` & `values-night/colors.xml`)
- **Version Control:** Git Branching Strategy with [Conventional Commits](https://www.conventionalcommits.org/)

---

## 📱 Implemented Applications

### 0. Hello World App
- **Branch:** `feature/hello-world`
- Initial project verifying Android Studio development environment setup and deployment to a physical device (Redmi Note 12).

### 1. Birthday Card App
- **Branch:** `feature/birthday-card`
- **Layout:** `RelativeLayout`
- Features a full-bleed vector/raster background (`centerCrop`) with customized typography and dynamic contrast between light and dark backgrounds.
- Personalized: *Happy Birthday Zain! — From Deema*.

### 2. Task Done Screen
- **Branch:** `feature/task-done`
- **Layout:** `LinearLayout` (Centered)
- Replicates standard completion flows with a high-resolution vector checkmark asset and adaptive background/text colors for Day/Night modes.

### 3. Compose Quadrant App
- **Branch:** `feature/quadrant`
- **Layout:** Weighted nested `LinearLayout` (`weightSum="2"`, `layout_weight="1"`)
- Mathematically splits the viewport into 4 equal quadrants across any screen density, each styled with unique palette variations in both Light and Dark themes.

### 4. Article Screen
- **Branch:** `feature/article`
- **Layout:** `ScrollView` with nested vertical `LinearLayout`
- Practices scrollable views (Module 1.3), displaying formatted long-form typography with line spacing (`lineSpacingExtra="4sp"`), image scaling, and fluid vertical scrolling.

### 5. Business Card App
- **Branch:** `feature/business-card`
- **Layout:** `RelativeLayout`
- Professional digital business card featuring the Android logo, personal credentials, and vector icons for direct contact details (Phone, GitHub/Social, Email).

---

## 🌿 Git Branching & Commits Log
All tasks were developed in isolated feature branches, pushed, and merged into `master` via Pull Requests:
- `setup/initial-resources` $\rightarrow$ Color palettes, vector drawables, and strings.
- `feature/hello-world` $\rightarrow$ Hello World setup.
- `feature/birthday-card` $\rightarrow$ Birthday card UI.
- `feature/task-done` $\rightarrow$ Task completion screen.
- `feature/quadrant` $\rightarrow$ 4-quadrant layout implementation.
- `feature/article` $\rightarrow$ Scrollable article implementation.
- `feature/business-card` $\rightarrow$ Personal business card screen.
- `master` $\rightarrow$ Main branch containing the integrated code and project documentation.

---

## 📸 Screenshots & Verification

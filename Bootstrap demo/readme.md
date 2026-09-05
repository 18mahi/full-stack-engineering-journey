# 💳 Responsive Pricing Cards

A responsive pricing card layout built using **HTML5, CSS3, and Bootstrap 5**.

This project focuses on practicing the **Bootstrap Grid System** and creating a responsive layout that adapts to different screen sizes.

---

## 📌 Project Overview

The project contains three pricing plans:

- 🆓 Free
- ⭐ Pro
- 🏢 Enterprise

The layout is designed using Bootstrap's responsive grid system.

### 💻 Desktop View

On medium and larger screens, all three pricing cards appear in one row.

```text
┌──────────────┐  ┌──────────────┐  ┌──────────────┐
│     Free     │  │      Pro     │  │  Enterprise  │
│              │  │              │  │              │
│     $0       │  │     $15      │  │     $30      │
│              │  │              │  │              │
│   Features   │  │   Features   │  │   Features   │
│    Button    │  │    Button    │  │    Button    │
└──────────────┘  └──────────────┘  └──────────────┘
```

### 📱 Mobile View

On smaller screens, the **Free** and **Pro** plans appear side-by-side, while the **Enterprise** plan takes the full width.

```text
┌──────────────┐  ┌──────────────┐
│     Free     │  │      Pro     │
│              │  │              │
│     $0       │  │     $15      │
└──────────────┘  └──────────────┘

┌─────────────────────────────────┐
│           Enterprise            │
│                                 │
│              $30                │
│                                 │
└─────────────────────────────────┘
```

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Grid System
- Responsive Web Design

---

## 📚 Bootstrap Concepts Practiced

This project helped me practice:

- Bootstrap Containers
- Bootstrap Rows
- Responsive Columns
- 12-column Grid System
- `col-6`
- `col-12`
- `col-md-4`
- Bootstrap Gutters
- Responsive Layouts
- Combining Bootstrap with Custom CSS

---

## 📐 Responsive Grid

The pricing cards use Bootstrap classes such as:

```html
<div class="col-6 col-md-4">
```

This means:

- **Mobile:** `6/12` columns → `50%` width
- **Medium and larger:** `4/12` columns → `33.33%` width

The Enterprise card uses:

```html
<div class="col-12 col-md-4">
```

This means:

- **Mobile:** `12/12` columns → `100%` width
- **Medium and larger:** `4/12` columns → `33.33%` width

---

## 🎨 Features

- ✅ Responsive pricing layout
- ✅ Three pricing plans
- ✅ Mobile-friendly design
- ✅ Bootstrap responsive grid
- ✅ Custom card borders
- ✅ Hover animations
- ✅ Responsive column arrangement
- ✅ Clean and simple UI
- ✅ Custom CSS styling
- ✅ Bootstrap 5 integration

---

## 📂 Project Structure

```text
responsive-pricing-cards/
│
├── index.html
├── style.css
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/18mahi/full-stack-engineering-journey/tree/8a9379f054be51d6b16786322748ca34f45175b1/Bootstrap%20demo
```

### 2. Open the Project

Open the project folder in **VS Code**.

### 3. Run the Project

Open `index.html` in your browser.

You can also use the **Live Server** extension in VS Code.

---

## 📱 Responsive Behavior

| Screen Size | Free | Pro | Enterprise |
|------------|------|-----|------------|
| Mobile | 50% | 50% | 100% |
| Medium+ | 33.33% | 33.33% | 33.33% |

The layout is achieved using Bootstrap's **12-column grid system**.

---

## 🎯 Learning Goals

The main goals of this project were:

- Understand Bootstrap's Grid System.
- Practice responsive column sizing.
- Understand how `col-*` and `col-md-*` work.
- Combine Bootstrap with custom CSS.
- Create responsive layouts without manually positioning elements.
- Practice clean and maintainable CSS.

---

## 🔮 Future Improvements

- ⬜ Add better card animations
- ⬜ Add icons to pricing plans
- ⬜ Add different visual styles for the Pro plan
- ⬜ Add a monthly/yearly pricing toggle
- ⬜ Improve accessibility
- ⬜ Add dark mode
- ⬜ Add more responsive breakpoints
- ⬜ Add functional buttons
- ⬜ Deploy the project using GitHub Pages

---

## 👩‍💻 Author

**Mahi Jindal**

Frontend Development Practice Project

---

## ⭐ Acknowledgement

Built as part of my journey to improve my **HTML, CSS, Bootstrap, and responsive web development skills**.

If you like this project, consider giving the repository a ⭐.

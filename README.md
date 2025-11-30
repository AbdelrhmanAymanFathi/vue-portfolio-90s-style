# Portfolio Website

This is a personal interactive portfolio built using **HTML**, **CSS**, and **Vue.js**. The design follows a retro console theme with animations, modals, tables, and fun tools.

## 🚀 Features

### **1. Interactive Tests & Projects Section**

* All items in *Courses & Certificates* are clickable.
* Clicking opens a custom **retro modal** with:

  * Title
  * Detailed explanation
  * Pass/Fail status (styled)
  * Project repo button (if applicable)
  * Date added (if exists)

### **2. Responsive Layout**

* Two-column design (About + Projects sections).
* Fully responsive for mobile, tablet, and desktop.
* Avatar and tables scale smoothly.

### **3. Days Lived Calculator (Game / Tool)**

A mini-app added to the right column.

Enter your birthday → it instantly calculates:

* Total days lived
* Approx years, months, days
* Auto-formatting with thousands separator
* "Today" button for quick input
* "Reset" button

All computed using Vue.js.

### **4. Accessibility Improvements**

* Keyboard navigation for rows (Enter key to open modal)
* Focus trapping inside modal
* ESC closes modal
* ARIA attributes for assistive tech

### **5. Clean & Modular JS Structure**

Using Vue 3 CDN with:

* Computed properties
* Methods for modal handling
* Input validation
* Smart repo link generator

## 🛠️ Tech Stack

* **HTML5**
* **CSS3** (custom, retro style)
* **Vue.js 3** (CDN build)
* Vanilla JavaScript for DOM utilities

## 📁 File Structure

```
index.html      # Main portfolio site
assets/         # Images, GIFs, icons (if used)
README.md       # This file
```

## 📦 How to Run

Simply open the project in any browser:

```
index.html
```

No build tools needed.

## 🎨 Customization

You can edit:

* Profile info
* Projects list
* Certificates
* Modal texts
* Calculator behavior

Everything is inside the `Vue.createApp()` config in the `<script>` tag.

## 📌 Future Improvements (Optional)

* Add a count-up animation to the days lived.
* Add confetti on milestones.
* Add pixel GIF icons.
* Connect real GitHub API to show pinned repos.

## 🧑‍💻 Author

**Abdelrhman Ayman Fathi**
Frontend Developer – Vue.js / JavaScript / Web UI

---


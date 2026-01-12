# Bedtime stories (Business Site)

This project is a **responsive business one-pager website** built as part of a training exercise focused on **HTML forms, clean code, and responsive layout**.

The page represents a fictional bedtime-story service and includes a hero header and a signup form that posts data to **HTTPBin** for inspection.

🔗 **Live site:**  
https://technigo-project-business-site.pages.dev

---

## 🧠 Project Goals

The main goals of this project were to:

- Practise building and structuring **HTML forms**
- Use multiple **input types** correctly
- Apply **semantic HTML** and **clean code principles**
- Create a **fully responsive layout** (mobile → tablet → desktop)
- Deploy a static site and document it properly

---

## 🖼️ Page Features

### Header
- Responsive hero section with an image
- Scales cleanly from mobile to desktop

### Signup Form
The form includes **multiple input types**, as required:

- Text inputs (name, email, optional child’s name)
- Password input
- Select dropdown (child’s age)
- Radio button group (available time for story)
- Checkbox group (story topics)
- Submit button

All form fields are clearly labeled, accessible, and styled consistently.

---

## 📤 Form Submission & HTTPBin

The signup form posts data to **HTTPBin**, which acts as a mock server.

**Form configuration:**
```html
<form action="https://httpbin.org/anything" method="post">

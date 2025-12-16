# 🎓 Student Portal – Angular Application

A simple Student Management Portal built using Angular and Bootstrap, allowing users to create, view, update, and delete student records through a clean UI with modal-based forms.

# 🚀 Features

- 📋 View list of students in card layout

- ➕ Add new student records

- ✏️ Edit existing student details

- ❌ Delete student records

- ✅ Form validation (required fields & email check)

- 🪟 Modal-based form UI

- 🎨 Responsive design using Bootstrap

---
# 🛠️ Tech Stack

- Angular (Standalone Components)

- TypeScript

- HTML5

- Bootstrap 5

- NgModel (FormsModule)



# 📂 Project Structure
```
src/
│── app/
│   ├── app.component.ts        # Component logic
│   ├── app.component.html      # UI template
│   ├── app.component.spec.ts   # Unit tests
│   ├── app.config.ts           # App configuration
│   ├── app.routes.ts           # Application routes
│
└── assets/
```

# 🧩 Core Functionalities
Student Fields

### Name *

### Mobile Number *

### Email *

### City

### State

### Pincode

### Address

(* required fields)


# ✅ Form Validation Rules

### Name, Mobile No, and Email are mandatory

### Email must contain @

### Validation messages shown after form submission


# ▶️ How to Run the Project

## 1️⃣ Install Dependencies
```
npm install
```
## 2️⃣ Run Development Server
```
ng serve
```

## 3️⃣ Open in Browser
```
http://localhost:4200/
```

# 📸 UI Overview

- Student cards display basic details

- “Add New” button opens modal

- Edit/Delete actions available per student

- Empty state message shown when no records exist



# 🔮 Future Enhancements

- 🔐 Authentication & authorization

- 🌐 Backend API integration

- 💾 Database persistence

- 🔍 Search & filter students

- 📄 Pagination

- 📱 Mobile-first improvements


# 👨‍💻 Author

Student Portal Angular App
Built for learning and demonstration purposes.

# 📄 LICENSE

Here is a ready-to-use MIT License you can add to your project as a LICENSE file (most common for Angular projects):
---
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

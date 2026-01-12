# Employee Management System (EMS)

A simple **Employee Management System** built with **HTML, CSS, and Vanilla JavaScript**. This project allows users to add, edit, delete, search, and filter employees, with data persisted using **Local Storage**.

---

## 🚀 Features

* ➕ Add new employees (Name, Job, Salary)
* ✏️ Edit existing employee details
* 🗑️ Delete employees with confirmation
* 🔍 Search employees by name, job, or salary
* 🧰 Filter employees by job category
* 💾 Persistent storage using `localStorage`
* 📱 Responsive and clean UI

---

## 🛠️ Technologies Used

* **HTML5** – Structure
* **CSS3** – Styling
* **JavaScript (ES6)** – Functionality
* **Local Storage** – Data persistence
* **Google Fonts (Roboto)** – Typography

---

## 📂 Project Structure

```
ems/
│── index.html
│── ems.css
│── ems.js
│── README.md
```

---

## ⚙️ How It Works

### 1. Add Employee

* Fill in **Full Name**, **Job**, and **Salary**
* Click **Add Employee**
* Data is saved in `localStorage`

### 2. Edit Employee

* Click **Edit** next to an employee
* Form is populated with existing data
* Update values and submit

### 3. Delete Employee

* Click **Delete**
* Confirm deletion to remove the employee

### 4. Search

* Use the search bar to find employees by:

  * Name
  * Job
  * Salary

### 5. Filter by Job Category

* Select a job category from the dropdown
* Table updates automatically

---

## 🧠 Key JavaScript Functions

* `add()` – Add or update employee
* `render()` – Display employees in table
* `setEdit(id)` – Enable edit mode
* `deleteemployee(id)` – Remove employee
* `searchemployee()` – Search employees
* `selectcateogry()` – Filter by job
* `updatestorage()` – Sync with localStorage

---

## 💾 Local Storage Format

```json
[
  {
    "id": 1700000000000,
    "fullname": "John Doe",
    "job": "developer",
    "salary": "50000"
  }
]
```

---

## ✅ How to Run the Project

1. Download or clone the repository
2. Open `index.html` in any modern browser
3. Start managing employees 🎉

---

## 📌 Future Improvements

* Salary validation & formatting
* Sorting by salary or name
* Dark mode
* Export to CSV
* Pagination for large datasets

---

## 👨‍💻 Author

Arunima S
Frontend Developer

---

## 📄 License

This project is open-source and free to use for learning purposes.

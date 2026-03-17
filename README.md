# 🎓 University Management System (JavaFX)

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=java\&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-0A0A0A?style=for-the-badge\&logo=java\&logoColor=white)
![IDE](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge\&logo=eclipse-ide\&logoColor=white)

A desktop-based **University Management System** developed using **JavaFX**.
This application helps manage student data, courses, and university operations efficiently.

---

## 🚀 Features

* 👨‍🎓 Student Registration & Management
* 📚 Course Management
* 🏫 Department Handling
* 🔍 Search & Filter Records
* 📝 Update & Delete Data
* 🎨 User-friendly GUI using JavaFX

---

## 🛠️ Technologies Used

* Java
* JavaFX
* Eclipse IDE
* Scene Builder (for UI design)
* MySQL *(optional for database integration)*

---

## 📂 Project Structure

```
University-Management-System/
│
├── src/
│   ├── application/
│   │   ├── Main.java
│   │   ├── Controller.java
│   │   ├── Model/
│   │   ├── View/
│
├── resources/
│   ├── FXML files
│   ├── CSS files
│
├── lib/
│   ├── JavaFX libraries
│
└── README.md
```

---

## ⚙️ Setup & Installation

### 1️⃣ Clone or Download Project

```bash
git clone https://github.com/your-username/university-management-system.git
```

---

### 2️⃣ Import into Eclipse

* Open Eclipse
* Go to **File → Import → Existing Projects into Workspace**
* Select the project folder

---

### 3️⃣ Configure JavaFX

* Download JavaFX SDK from: https://gluonhq.com/products/javafx/
* Add all `.jar` files from `javafx/lib` to project build path

---

### 4️⃣ Add VM Arguments

Go to **Run → Run Configurations → Arguments**

```bash
--module-path "C:\javafx-sdk-21\lib" --add-modules javafx.controls,javafx.fxml
```

---

### 5️⃣ Run the Project

* Right-click `Main.java`
* Click **Run As → Java Application**

---

## 🐞 Common Issues

### ❌ JavaFX runtime not found

✔ Ensure VM arguments are set correctly

### ❌ FXML not loading

✔ Check file paths and controller linkage

### ❌ Build path errors

✔ Clean project: `Project → Clean`

---

## 📸 Screenshots

> Add screenshots of your UI here to showcase your project

---

## 🤝 Contributing

Contributions are welcome! 🚀
Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Pratik Kumbhar**

---

## ⭐ Acknowledgements

* JavaFX Documentation
* Open-source community
* Scene Builder

---

## 💡 Future Enhancements

* Add database integration (MySQL)
* Implement login authentication system
* Improve UI/UX design
* Add reporting & analytics dashboard

---

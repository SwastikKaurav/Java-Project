# Java-Project

Campus Course Manager

The "Campus Course Manager" is a console-based application developed in Java. It serves as a foundational Course Management System designed to streamline the administrative tasks of an educational institution. The system allows for the management of two core entities: Students and Courses. It provides functionalities to add, view, and manage these entities through an intuitive menu-driven interface. This project demonstrates the practical application of core Java concepts like Object-Oriented Programming (OOP), data structures (ArrayList), and basic input/output operations


## Features

The application provides a text-based, menu-driven interface with the following core functional requirements:

### Student Management
* **Add Student:** The system allows an administrator to register a new student with details like ID, name, and email.
* **View Students:** The system displays a list of all registered students.

### Course Management
* **Add Course:** The system allows an administrator to add a new course with details like code, title, and credits.
* **View Courses:** The system displays a list of all available courses.

### Data Overview
* **Summary View:** The system provides a summary view showing the total count of students and courses, along with their lists.

---

## Technologies & Tools Used

This project focuses on demonstrating core Java skills.

---

## Steps to Install & Run the Project

### Prerequisites

1.  **Java Development Kit (JDK):** Must be installed (version 8 or above).
2.  **IDE:** A standard Java Integrated Development Environment (IDE) like **IntelliJ IDEA, Eclipse, or NetBeans** is recommended.

### Installation & Execution

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/SwastikKaurav/Java-Project.git](https://github.com/SwastikKaurav/Java-Project.git)
    ```

2.  **Navigate to the Project:** Locate the `CampusCourseManager` or main project folder within the cloned repository.

3.  **Open in IDE:** Import the project folder into your preferred Java IDE.

4.  **Run the Main Class:**
    * The entry point for the application is the `main` method within the **`Main` class**.
    * Locate the `Main.java` file and execute it from your IDE.

5.  **Interaction:** The application will launch with a text-based menu in the console, prompting for user input.

---

## 🧪 Instructions for Testing

The system was tested using manual Unit Testing, Integration Testing, and Input Validation Testing.

1.  **System Startup Test:** Run the application and confirm the main menu loads without errors.
2.  **Feature Testing (Integration):**
    * Add a new student via the **Manage Students** menu.
    * Verify the addition by selecting **View All Data** and checking the student list.
    * Perform the same steps for adding a course.
3.  **Input Validation Testing:**
    * At any menu prompt asking for a number, try entering text or a non-integer value.
    * The system should handle basic user input errors gracefully without crashing.
4.  **Persistence Test (Expected Behavior):**
    * Add new student/course data.
    * Exit the program (option 0).
    * Re-run the program and confirm that the newly added data is **lost**, as all data is stored in-memory for the initial version.

---

## 📸 Example Console Output

The application is entirely console-based. Here is an example of the expected interaction flow:

```text
Welcome to Campus Course Manager!
- My Java University Project -
Loaded sample data: 2 students, 2 courses
===== MAIN MENU =====
1. Manage Students
2. Manage Courses
3. View All Data
4. File Operations
0. Exit
Choose an option: 3
=== CURRENT DATA ===
Students: 2
Courses: 2
All Students
1. S001 - John Doe (john@university.edu)
2. S002 - Jane Smith (jane@university.edu)
All Courses
1. CS101: Introduction to Programming (3 credits)
2. MA201: Calculus 1 (4 credits)

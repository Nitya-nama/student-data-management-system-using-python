

**1. Classes & Functions**
- **`Student` Class:**  
  - Validates name, roll number, and marks.
  - Calculates the grade based on marks.
  - Converts student data into a list format for CSV storage.

- **`GradeManager` Class:**  
  - Manages student records in **grades.csv**.
  - Adds, views, searches, and deletes student records.

- **Helper Functions:**
  - **`get_valid_input()`** → Ensures correct input format using regex.
  - **`get_valid_marks()`** → Ensures marks are between 0-100.

 **2. `main()` Function**
- **Displays a menu** for user operations.
- Handles **user input** to perform actions like adding, searching, and deleting students.

---

 **How It Works**
1. **Runs `main()`** → Displays the menu.
2. **User selects an option** (1-5).
3. **Performs the operation** (e.g., adding a student, searching by roll number).
4. **Loop continues** until the user exits.

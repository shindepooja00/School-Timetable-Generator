# School Timetable Generator

---

## 📊 Project Overview

This project automates the creation of school timetables for Jr. Kg, Sr. Kg, and 1st standard across divisions A, B, C, and D. It ensures error-free scheduling with specified periods, breaks, and assemblies.

---

## 🛠️ Libraries & Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  ![Datetime](https://img.shields.io/badge/Datetime-32CD32?style=for-the-badge)  ![CSV](https://img.shields.io/badge/CSV-FFD700?style=for-the-badge)

| **Library/Technology** | **Purpose**                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `Python`               | Core programming language for implementation                               |
| `pandas`               | Data manipulation and storage, used for creating and exporting timetables |
| `datetime`             | Time calculations for generating time slots                               |
| `CSV`                  | Exporting the finalized timetable for administrative use                 |

---

## 📅 Timetable Features

| **Category**            | **Details**                                                              |
|-------------------------|--------------------------------------------------------------------------|
| **Classes**             | Jr. Kg, Sr. Kg, 1st                                                     |
| **Divisions**           | A, B, C, D                                                              |
| **Period Duration**     | 30 minutes                                                              |
| **Lunch Breaks**        | Jr. Kg & Sr. Kg: 12:45 PM - 1:15 PM, 1st: 9:25 AM - 9:45 AM, 12:45 PM   |
| **Assembly**            | Every Tuesday at 10:45 AM                                               |

---

## 📋 Implementation Steps

### 1. **Defining Constants**
- Declared school timings, break schedules, and class details.
- Ensured structured inputs for smooth calculations.

### 2. **Generating Time Slots**
- Used the `datetime` library to create 30-minute intervals for each day.
- Function `create_time_slots` dynamically calculates and returns slot lists.

### 3. **Adding Breaks and Assembly**
- Integrated breaks and assembly into the timetable for each class.
- Ensured non-overlapping and accurate scheduling.

### 4. **Assigning Subjects**
- Distributed subjects evenly using a round-robin approach.
- Avoided conflicts with predefined breaks and assemblies.

### 5. **Structuring Data**
- Organized daily schedules into dictionaries for each division and class.
- Formatted data into `pandas` DataFrames for clarity.

### 6. **Saving Timetables**
- Exported each timetable as a `.csv` file using `pandas.to_csv()`.
- Ensured easy access and usability for school administrators.

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/SchoolTimetableGenerator.git
   ```
2. Run the script `timetable_generator.py` using Python.
3. Find the generated `.csv` files in the output folder.

---

## 📈 Future Enhancements

- 🌐 Add multi-grade and multi-period support.
- 📊 Visualize timetables with charts and graphs.
- 🧠 Integrate AI for predictive scheduling.

---

## 💬 Contact Me

For queries, collaborations, or feedback, feel free to reach out:

- 📧 Email: [shindepooja1014@gmail.com](mailto:shindepooja1014@gmail.com)
- 💼 LinkedIn: [Pooja Shinde](https://www.linkedin.com/in/pooja-shinde-1824592a5/)

---

Thank you for exploring this project! Let’s make scheduling smarter and more efficient. 😊


# 📊 Zylentrix Online Learning Platform – User Engagement Analysis (Power BI)

## 🧠 Project Summary

This Power BI project analyzes student behavior on Zylentrix’s online education platform. It explores how learners engage with content, how long they spend, how much they complete, and how satisfied they are with the courses. The project was completed as part of a **Data Analyst Internship Assignment** to demonstrate analytical thinking, dashboard building, and insight generation.

---

## 📁 Dataset Overview

The dataset contains:
- `students.csv`: Student ID, Name, Age, Gender, Location, Enrolment Date
- `course_activity.csv`: Course sessions, Time Spent (mins), Completion %, Date
- `feedback.csv`: Course Rating (1–5), Text Feedback, Course ID, Student ID

---

## 🎯 Business Questions Addressed

1. What is the **average course completion rate** across all courses?
2. Which course has the **highest and lowest engagement time**?
3. How does student engagement vary by **age group** and **location**?
4. What is the **average feedback rating per course**?
5. Is there a correlation between **feedback rating** and **completion rate**?
6. Who are the **top 3 student segments** in terms of engagement & satisfaction?

---

## 🧪 Dashboard Components

Key visuals and DAX insights:
- **KPI Cards**:  
  - `Overall Avg Completion Rate`  
  - `Avg Feedback Rating`  
  - `Avg Time Spent (mins)`
- **Bar Charts**:
  - Top 5 courses by engagement time
  - Feedback ratings by course
- **Scatter Plot**:
  - Correlation between completion % and rating
- **Slicers**:
  - Filter data by `Course`, `Gender`, `Age Group`, `Location`
- **Heatmap**:
  - Engagement by region and course
- **Line Chart**:
  - Engagement trends over time

---

## 📈 Key Insights

- 👩‍🎓 Younger students (<20) spent more time.
- 🧭 Kolkata & Delhi students were most engaged.
- 📘 PY202 has highest average rating (3.28).
- 🛠️ WD404 received relatively lower ratings.
- 📊 Weak correlation (-0.05) between completion % and feedback.

---

## 💡 Recommendations

1. Offer personalized nudges to highly engaged but low-completion students.
2. Target younger audiences with bite-sized modules.
3. Investigate student expectations vs delivery for top engaging courses.

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop** – Visualization & Dashboard
- **Power Query** – Data cleaning and merging
- **DAX** – Custom measures (completion rate, averages, correlations)
- **Relational Data Modeling** – Connecting students, activity, and feedback

---

## 🖼️ Dashboard Preview
 ![Screenshot 2025-04-22 213634](https://github.com/user-attachments/assets/df8708a0-9856-4679-a497-07292e4da1dc)


## 📂 Repository Structure
📁 zylentrix-user-engagement-analysis/
├── Data Analyst Intern Assignment.pbix     # Full Power BI dashboard
├── README.md                               # Project overview and documentation
└── assets/
    └── dashboard-preview.png               # Optional visual preview
 
---

## 👨‍💻 Author

**[Sunkara Venkataramana]**  
🔗 [LinkedIn](https://www.linkedin.com/in/svramana1/) 
📫 [Vramana086@gmail.com]




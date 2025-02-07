# Exam Scheduler in Python  

## 📌 Overview  
This project is an **Exam Scheduler** built using **Python (Jupyter Notebook)**. It schedules exams efficiently based on predefined constraints while aiming to maximize the **fitness score** for an optimal solution.  

## 🚀 Features  
- **Automatic scheduling** of exams within predefined time slots.  
- **Constraint-based optimization** to ensure fairness and efficiency.  
- **Fitness score calculation** to evaluate scheduling quality.  
- **Flexible scheduling** to handle varying numbers of classrooms and exams.  

## 📌 Constraints  
The scheduler follows these **hard constraints** to ensure a valid schedule:  

1. **Time Slots:** Two slots per day:  
   - **Morning Slot:** 9:00 AM - 12:00 PM  
   - **Noon Slot:** 2:00 PM - 5:00 PM  
2. **Exam Duration:** Each exam lasts **3 hours**.  
3. **Time Boundaries:** Exams must be scheduled **between 9:00 AM and 5:00 PM**.  
4. **Classroom Utilization:** Not all classrooms need to be used each day.  
5. **Fitness Score:** Higher values indicate a **better schedule**.  
6. **Slot Consistency:** Any day with exams will have both **morning and noon** slots occupied.  

## 📂 Installation & Usage  
1. **Clone the repository:**  
   ```sh
   git clone https://github.com/yourusername/exam-scheduler.git
   cd exam-scheduler
## 📜 License  
This project is licensed under the **MIT License**.  


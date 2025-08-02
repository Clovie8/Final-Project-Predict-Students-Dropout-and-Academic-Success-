# Final Project 
# Project Title: Predict Students Dropout and Academic Success
This project aims to analyze various demographic, socio-economic, and academic factors to predict whether a student will graduate, drop out, or remain enrolled. By identifying at-risk students early, institutions can take proactive measures to improve retention rates and academic success.


## **Dataset Overview**

* **Rows:** 4,424
* **Columns:** 37
* **Type:** Educational dataset tracking **students’ demographics, academic records, and socio-economic factors**.
* **Goal:** Predict **Target** (student outcome: e.g., *Graduate*, *Dropout*, *Enrolled*).
* **No geographic coordinates** (latitude/longitude), so **a map is not strictly needed** unless you group by nationality.


## **Main Column Groups**

### **1. Demographic Information**

* **Marital status** – Student’s marital status (coded as numbers).
* **Gender** – 1 = Male, 2 = Female (coded).
* **Age at enrollment** – Age when student enrolled.
* **Nacionality** – Coded country of origin.
* **International** – 1 if international student.

### **2. Application & Enrollment Details**

* **Application mode** – How they applied (exam, transfer, etc.).
* **Application order** – Preference order.
* **Course** – Code of degree program.
* **Daytime/evening attendance** – 1 = Day, 0 = Evening.
* **Previous qualification** – Level before this course.
* **Previous qualification (grade)** – Grade from previous study.

### **3. Parental Information**

* **Mother’s qualification & occupation** – Education level and job.
* **Father’s qualification & occupation** – Education level and job.

### **4. Academic Performance**

* **Admission grade** – Entrance exam grade.
* **Curricular units 1st/2nd semester** – Credit, enrollment, evaluations, approved units, grades, no evaluations.

### **5. Socio-economic Indicators**

* **Unemployment rate, Inflation rate, GDP** – Economic conditions during enrollment.

### **6. Special Status**

* **Displaced** – 1 if displaced student.
* **Educational special needs** – 1 if any learning disability.
* **Debtor** – If they owe tuition.
* **Tuition fees up to date** – Paid or not.
* **Scholarship holder** – 1 if they have a scholarship.

### **7. Target Variable**

* **Target** – Student outcome:

  * **Graduate** – Completed program successfully.
  * **Dropout** – Left before finishing.
  * **Enrolled** – Still studying.


## **Why This Dataset Is Useful**

* Can be used for **classification modeling** to predict whether a student will **graduate, drop out, or remain enrolled**.
* Suitable for **policy-making** and **student success analysis**.
* Offers **socio-economic + academic + demographic** perspectives.


## **Map Usage**

* No latitude/longitude → a detailed map is **not** necessary.
* You **can** make a **country-level map** in Power BI using **Nacionality** to see the distribution of students by origin.

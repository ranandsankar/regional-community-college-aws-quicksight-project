# Q Topic Details

## Topic Name
**Regional Community College Student Data**

## Description
Q&A environment for understanding student enrollment data.

## Fields Included (All Required Fields)
Student Type  
NationalOrigin  
Gender  
StudentClassification  
Course  
Grade  
TestScore  
Semester  
CourseId  
Professor  
Credit  
CostPerCourse  
EvaluationScore  
StudentName  
StudentId  
AcademicYear  
EnrollmentDate  
GraduationDate  
Major  
Age

# Named Entities (Required)
## Entity 1 — Student Details
**Description:** Information about enrolled students  
**Field Ranking:**  
Student Name  
Semester  
Course  
Test Score  
Grade  
Student Classification  
Student Type  
Major  
Gender  
NationalOrigin  
Credit  
Enrollment Date  
Graduation Date  
Student Id  

## Entity 2 — Course Details
**Field Ranking:**  
Course  
Professor  
Cost per Course  
Academic Year  
Semester  
Course Id  

## Entity 3 — Professor Evaluation
**Field Ranking:**  
Professor  
Course  
Semester  
Academic Year  
Student Name  
Evaluation Score  

# Verified Questions (Required)
### 1. Which instructors got the best average evaluations?  
**Verified:** Yes  
### 2. Which courses are the most expensive?  
**Corrected Interpretation:**  
Changed to *average* CostPerCourse  
**Verified:** Yes  
### 3. Additional Verified AI-Generated Questions
- What is the average evaluation score by course?  
- What is the number of students per major?  
- What is the average test score by student type?  

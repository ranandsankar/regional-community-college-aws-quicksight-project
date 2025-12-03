# Dataset Details

## Dataset Used
**Q - Student Enrollment**  
Imported from the built-in QuickSight **Student Enrollment Statistics** sample.


## Dataset Field Names (Required)
- Age  
- AcademicYear  
- Major  
- Course  
- CourseId  
- Professor  
- Gender  
- Grade  
- TestScore  
- CostPerCourse  
- Credit  
- Semester  
- StudentId  
- StudentName  
- StudentClassification  
- EnrollmentDate  
- GraduationDate  
- HomeOfOrigin (renamed to **NationalOrigin**)  
- EvaluationScore  

## Field Transformation

### ➤ Renamed Field
| Original | New Name | Description |
|----------|----------|-------------|
| HomeOfOrigin | **NationalOrigin** | Country of Residence on admission application |

---

## Calculated Field (Required)

### **Student Type**
```text
ifelse({Age} < 30, "Youth", "Adult Continuing Education")

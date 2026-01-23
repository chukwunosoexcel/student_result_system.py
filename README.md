# student_result_system.py
Project Title: Student Result Management System
Name: Chukwunoso Excel Munachinso
Matric Number: 24/14500
1. Planning
The aim of this project is to design and implement a simple system that records and displays a
student’s academic result using Python programming language.
2. Requirements Analysis
Functional Requirements include entering student score and displaying result. Non-functional
requirements include simplicity, speed, and ease of use.
3. System Design
The system is designed with the following modules: get_student_details(), calculate_result(), and
display_result(). These names are maintained consistently in the implementation.
4. Implementation
def get_student_details():
name = "Chukwunoso Excel Munachinso"
matric_number = "24/14500"
score = int(input("Enter student score: "))
return name, matric_number, score
def calculate_result(score):
if score >= 50:
return "Pass"
else:
return "Fail"
def display_result(name, matric_number, score, result):
print("Name:", name)
print("Matric Number:", matric_number)
print("Score:", score)
print("Result:", result)
name, matric_number, score = get_student_details()
result = calculate_result(score)
display_result(name, matric_number, score, result)
5. Testing
The system was tested using different scores to ensure correct Pass or Fail output.
6. Deployment
The project was deployed by uploading the source code to a GitHub repository.
7. Maintenance
Future updates may include storing multiple student records and grading systems

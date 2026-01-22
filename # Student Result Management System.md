# Student Result Management System  
  
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
    print("\n--- Student Result ---")  
    print("Name:", name)  
    print("Matric Number:", matric_number)  
    print("Score:", score)  
    print("Result:", result)  
  
  
# Main Program  
name, matric_number, score = get_student_details()  
result = calculate_result(score)  
display_result(name, matric_number, score, result)  

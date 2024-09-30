- 👋 Hi, I’m @ParsaYekta
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ParsaYekta/ParsaYekta is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->student={
    "first_name" :str(),
    "last_name" :str(),
    "birthday" :str(),
    "code_meli" :int(),
    "student_code" :int(),
    "courses" :list(),
    "grades" :list(),
}
from os import system
clear = lambda : system("cls")


students=[]

def add_student():
    clear()
    global students                 #optional code
    student = {}
    student["first_name"] = input("Enter your first_name : ")
    student["last_name"] = input("Enter your last_name : ")
    student["birthday"] = input("Enter your birthday : ")
    if
    student["code_meli"] = input("Enter your code_meli : ")
    if
    student["student_code"] = input("Enter your student_code : ")
    if
    student["courses"] = input("Enter your courses : ")
    student["grades"] = input("Enter your grades : ")
    if
    students.append(students)
    input("\nThis student added to database successfully, Press Enter to return menu")


def list_students():
    for student in students :
        print(30*"-")
        print(" first_name :",student["first_name"])
        print(" last_name :",student["last_name"])
        print(" birthday :",student["birthday"])
        print(" code_meli :",student["code_meli"])
        print(" student_code :",student["student_code"])
        print(" courses :",student["courses"])
        print(" grades :",student["grades"])
    input("\nPress Enter to return")

def find_student():
     student_code = input("Enter student_code to find the student : ")
     for student in students : 
        if student["student_code"] == student_code  :
            print("First_name :",student["first_name"])
            print("Last_name :",student["last_name"])
            print("Birthday :",student["birthday"])
            print("Code_meli :",student["code_meli"])
            print("Student_code :",student["student_code"])
            print("Courses :",student["courses"])
            print("Grades :",student["grades"])


            break
     else :
        input("\nThis studnt Doesn t exsit in students database! Press enter to continue ...")

def delete_student():
    clear()
    student_code = input("Enter Student_code to delete the student : ")
    for student in students :
        if student["student_code"] == student_code :
            students.remove(student)
            input("\nThis student has been delete from database !")
            break

def save_students():
    student_code = input("Enter S to save the students : ")
    for student in students :
        if student["student_code"] == student_code :
            students.save(student)
            input("\nThis student was saved !")
            break
            

def change_courses():
    student_code = input("Enter C to change the students : ")
    for student in students :
     if student["student_code"] == student_code :                                                                                                                                                            


     
      input("\nThis student was change courses !")
      break

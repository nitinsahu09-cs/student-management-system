# student-management-system
A simple Student Management System made using Python.
Advanced Student Management System in Python

Beginner-Friendly Professional Project for GitHub & LinkedIn

students = []

def add_student(): print("\n===== Add Student =====") name = input("Enter student name: ")

if name.strip() == "":
    name = "Nitin"
roll = input("Enter roll number: ")
course = input("Enter course name: ")

student = {
    "Name": name,
    "Roll": roll,
    "Course": course
}

students.append(student)
print("Student added successfully! ")

def view_students(): print("\n===== Student Records =====")

if len(students) == 0:
    print("No student records found.")
    return

for index, student in enumerate(students, start=1):
    print(f"\nStudent {index}")
    print(f"Name   : {student['Name']}")
    print(f"Roll   : {student['Roll']}")
    print(f"Course : {student['Course']}")

def search_student(): print("\n===== Search Student =====") roll = input("Enter roll number to search: ")

found = False

for student in students:
    if student['Roll'] == roll:
        print("\nStudent Found ")
        print(f"Name   : {student['Name']}")
        print(f"Roll   : {student['Roll']}")
        print(f"Course : {student['Course']}")
        found = True
        break

if not found:
    print("Student not found ")

def delete_student(): print("\n===== Delete Student =====") roll = input("Enter roll number to delete: ")

for student in students:
    if student['Roll'] == roll:
        students.remove(student)
        print("Student deleted successfully ")
        return

print("Student not found ")

while True: print("\n========== Student Management System ==========") print("1. Add Student") print("2. View Students") print("3. Search Student") print("4. Delete Student") print("5. Exit")

choice = input("Enter your choice (1-5): ")

if choice == '1':
    add_student()

elif choice == '2':
    view_students()

elif choice == '3':
    search_student()

elif choice == '4':
    delete_student()

elif choice == '5':
    print("Thank you for using Student Management System ")
    break

else:
    print("Invalid choice! Please try again.")

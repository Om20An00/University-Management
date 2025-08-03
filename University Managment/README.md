🎓 University Management System
The University Management System is a console-based C++ application that allows administrators to manage student records efficiently. It supports adding, searching, and updating student information stored in a text file. The application uses object-oriented principles and file handling to simulate a simple database.

📌 Features
➕ Add Student Record
Collects and stores student Roll No, Name, Subject, and Address.

🔍 Search Student by Roll No
Searches and displays student information based on the entered roll number.

✏️ Update Student Address
Updates the address of a student with the given Roll No.

💾 Persistent Storage
All data is saved in a .txt file at location D:/university.txt.

🛠️ Tech Stack
Language: C++

Environment: Console

Libraries Used:

iostream – for input/output

fstream – for file handling

windows.h – for sleep and screen clearing (Sleep, system("cls"))

🧾 File Structure
university.txt – stores the student records in plain text format.

university temp.txt – used temporarily during update operations.

🚀 Getting Started
✅ Prerequisites
Windows OS

C++ compiler (e.g., GCC via MinGW, Turbo C++, or Visual Studio)

▶️ Run the Program
Open a terminal or IDE.

Compile the file:

bash
Copy
Edit
g++ university_management.cpp -o university.exe
Run the executable:

bash
Copy
Edit
./university.exe
📁 Sample Data Format (Stored in D:/university.txt)
yaml
Copy
Edit
101 : JohnDoe : ComputerScience : NewYork

102 : AliceSmith : Physics : California
📸 UI Preview (CLI)
markdown
Copy
Edit
Welcome To University Management System
***************************************
1. Add Student
2. Search Student
3. Update Data Of Student
4. Exit
Enter Your Choice: _
🧠 Concepts Demonstrated
Object-Oriented Programming (Encapsulation)

File Handling (Read/Write/Update)

Console UI Navigation

Basic Data Validation


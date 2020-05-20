# ProjectForFinalsForJava (Student registration)
First of all I took aikachuwa's project(https://github.com/aikachuwa/RegistrationFormApp4) as template. But there were a lot of things that, I think, are not needed for my project as project for Final Exams.
## Beginning
First I took 2 classes from this project. They are Main and Registration classes. Then created new empty project with JavaFX. To make empty project work I performed some actions. First is importing library of JavaFX to my project. Second it edit run configurations (VM options)
## What did I change
I renamed all lable fields. After all it is student registration. I changed the positions of labels and text fields. Also window sizes have been fixed, so it has minimum and maximum sizes. List of students that are registered was added. To work with classes, Student class was created. It has all parameters that are introduced in our Student-ID cards. For example: names, surnames, ID in university, department and more. In Registration class I added method getStudents to be able get data from txt file. Txt file is for "data-base" in my project. When we click "Submit" button project firstly checks is there txt file named "data-base" (if not, it creates new). Also it checks is it has something written on it and adds some data or writes. To make label for student names and IDs I had to use massive for labels. And everytime JFrame refreshes, it gets new information from txt file. Refreshing method I did by creating new JFrame and closing the previous one.

## Let me show you table from "Project Proposal.pdf" file

Title of the project | Student Registration
--- | --- 
Background | It is very interesting to know how do system make data bases to work with them in future. And I wanted to know how do people automize some easy stuff in modern world
Aim of the project | Aim is to make work with data about students easier
Expected outcomes | More knowledge in Java and its libraries, almost completed desktop app
Proposed activities | -
Estimative budget | No budget
Proposed partners | No partners
Git repository link | https://github.com/Pamirbek/ProjectForFinalsForJava/blob/master/README.md
Contact person | Name: Pamirbek, surname: Almazbekov, email: pamirbek.almazbekov@iaau.edu.kg, phone number: +996701222002

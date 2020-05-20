# ProjectForFinalsForJava (Student registration)
First of all I took aikachuwa's project(https://github.com/aikachuwa/RegistrationFormApp4) as template. But there were a lot of things that, I think, are not needed for my project as project for Final Exams.

## Project report
### What did I change
I took 2 classes from template. They are Main and Registration classes. Then renamed all lable fields in the template. After all it is student registration. I changed the positions of labels and text fields. Also window sizes have been fixed, so it has minimum and maximum sizes. In Registration class I added method getStudents to be able get data from txt file. Also I added button that opens new window with all information about registered students.
### GUI
I created new empty project with JavaFX. To make empty project work I performed some actions. First is importing library of JavaFX to my project. Second it edit run configurations (VM options). In project I added a lot of labels and text fields that are were placed in massive to control them in future with loops. Also to I needed to create a new window with help of button. Refreshing method I did by creating new JFrame and closing the previous one. In the end I slightly understood how to work with JFrame.
### Database
Txt file is for "database" in my project. When we click "Submit" button project firstly checks is there txt file named "database" (if not, it creates new). Also it checks is it has something written on it and adds some data or writes. To make label for student names and IDs I had to use massive for labels. And everytime JFrame refreshes, it gets new information from txt file. Every new line becomes parameter for Student class and every 7th lines is start of new class.
### Exceptions
In console you can see the exception if you leave one of the inputs empty. And that is not all. If student does not fill email with "@" and "." it will throw an exception again, but this time saying that email was not written properly. Also for text field "Date of birth" there is exception for character "/". Not only exception will appear in console, but also text describing the input problem under buttons "Submit" and "Clear".
### Classes
To work with classes, Student class was created. It has all parameters that are introduced in our Student-ID cards. For example: names, surnames, ID in university, department and more. And I use these classes in a new window. And to show information about them I used getters method. Also every JFrame is another class. For instance: Registration and Students windows are two classes in my project.

### Let me show you table from "Project Proposal.pdf" file

Title of the project | Student Registration
--- | --- 
Background | It is very interesting to know how do system make databases to work with them in future. And I wanted to know how do people automize some easy stuff in modern world
Aim of the project | Aim is to make work with data about students easier
Expected outcomes | More knowledge in Java and its libraries, almost completed desktop app
Proposed activities | Edit code to make a project
Estimative budget | No budget
Proposed partners | No partners
Git repository link | https://github.com/Pamirbek/ProjectForFinalsForJava/blob/master/README.md
Contact person | Name: Pamirbek, surname: Almazbekov, email: pamirbek.almazbekov@iaau.edu.kg, phone number: +996701222002

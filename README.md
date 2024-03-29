# Android-App-Student-Term-Tracker

This Android app for is made for students. Students can add, edit, delete terms, courses, and assessments. Due dates are shown in notifications.

## Home Screen
![Home screen](main.png?raw=true "Home Screen")

Input
Each of the following needs to be input into the application:
*  terms, including the following:
    -      the term title (e.g., Term 1, Term 2)
    -      the start date
    -      the end date
*  courses, including the following:
    -      the course title
    -      the start date
    -      the anticipated end date
    -      the status (e.g., in progress, completed, dropped, plan to take)
    -      the course mentor name(s), phone number(s), and email address(es)
    -      objective and performance assessments associated with each course
*  the ability to add optional notes for each course
*  the ability to set alerts or notifications for the start and end date of each course
*  the ability to set alerts for goal dates for each objective and performance assessment


Output
Each of the following needs to be displayed by the application on a separate screen:
*  the navigation panel
*  a list of terms
*  a detailed view of each term, including the following:
    -      the title (e.g., Term 1, Term 2)
    -      the start date
    -      the end date
*  a list of courses for each term
*  a detailed view of each course, including the following:
    -      the course title
    -      the start date
    -      the anticipated end date
    -      assessments
*  a list of performance and objective assessments for a selected course
*  a detailed view of each objective and performance assessment, including the following:
    -      the due date for a selected course
    -      notes for the selected course
    -      sharing features (e.g., email, SMS)
REQUIREMENTS
________________


A. Create an Android (version 4.0 or higher) mobile application with the following functional requirements:
1. Include the following information for each  term:
    -  the term title (e.g., Term 1, Term 2, Spring Term)
    -  the start date
    -  the end date
2. Include features that allow the user to add as many terms as needed.
3. Implement validation so that a term cannot be deleted if courses are assigned to it.
4. Include features that allow the user to do the following for each  term:
a. add as many courses as needed
b. display a list of courses associated with each  term
c. display a detailed view of each  term, including the following information:
    -  the term title (e.g., Term 1, Term 2, Spring Term)
    -  the start date
    -  the end date
5. Include the following details for each  course:
    -  the course title
    -  the start date
    -  the anticipated end date
    -  the status (in progress, completed, dropped, plan to take)
    -  the course mentor names, phone numbers, and e-mail addresses
6. Include features that allow the user to do the following for each  course:
a. add as many assessments as needed
b. add a minimum of one optional note per course
c. enter, edit, and delete course information
d. display optional notes
e. display a detailed view of the course, including the due date
f. set alerts for the start and end date, that will trigger when the application is not running
g. share notes via a sharing feature (either e-mail or SMS)
7. Include features that allow the user to do the following for each  assessment:
a. add performance and objective assessments for each  course, including the titles and due dates of the assessments
b. enter, edit, and delete assessment information
c. set alerts for goal dates, that will trigger when the application is not running


B. Design the following screen layouts, including appropriate GUI (graphical user interface) elements (e.g., navigation, input, and information) for each  layout:
    -  home screen
    -  list of terms
    -  list of courses
    -  list of assessments
    -  detailed course view
    -  detailed term view
    -  detailed assessment view


C. Create a scheduler and progress tracking application as part of your mobile application from part A.


Note: This can be the implementation of part A.


1. Include the following implementation requirements in the application from part C. Be sure your application is a minimum version 4.0 mobile application:
    *  an ArrayList
    *  an intent
    *  navigation capability between multiple screens using activity
    *  three activities
    *  events (e.g., a click event)
    *  the ability to work in portrait and landscape layout
    *  interactive capability (e.g., the ability to accept and act upon user input)
    *  a database to store and retrieve application data
    *  an application title and an icon
    *  notifications or alerts
    *  the use of both declarative and programmatic methods to create a user interface


2. Include the following interface requirements in the application from part C:
    *  the ability to scroll vertically
    *  an action bar
    *  two layouts
    *  input controls
    *  buttons


D. Create a storyboard to demonstrate application flow that includes each  of the menus and screens from part B.


E. Provide screen shots of generating the signed APK to demonstrate that you have created a deployment package.


Note: Verify that all the required functions of your application are working by executing the apk file.


F. Reflect on the creation of your mobile application by doing the following:
1. Explain mobile application development through the context of the architecture involved, including hardware and software capabilities and limitations.
a. Identify the version of the operating system your application was developed under and is compatible with.
2. Describe (suggested length of 1–2 paragraphs) the challenges you faced during the development of the mobile application.
3. Describe (suggested length of 1–2 paragraphs) how you overcame each  challenge discussed in part F2.
4. Describe (suggested length of 1–2 paragraphs) what you would do differently if you did the project again.
5. Describe how emulators are used and the pros and cons of using an emulator vs. using a development device.

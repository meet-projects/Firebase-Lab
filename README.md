# Firebase Lab

## Objective: 
In this lab, you will learn how to use Firebase in your Android Studio Apps, being able to read and store data from your users!  

By the end of this lab, you will your Android Studio project done, having implemented many aspects of Android Studio, including: Firebase & ListView.  

## Instructions:

In this lab, you will continue from the previous labs and you will be implementing Firebase!  

1. Connecting **Firebase Project** to Android Studio Project:
    - Create a new project in Firebase and set up `Authentication` & `Realtime Firebase`.
    - Sign in your email in Android Studio.
    - Open Tools --> Firebase --> Authentication --> Connect.
    
2. **Firebase Authentication**:
    - Add the `Authentication` **dependency** to your project.
    - In the `SignUpActivity`:
        - Create a function called `create_user`, that takes **email** & **password**.
        - In the function add the **Firebase Signup**.
        - When the Task is **successful** go to `HomeActivity`, otherwise display a message, saying "Authentication Failed".
    - In the MainActivity do the same as before but adapted to Signin.
    - When the User signs out in HomeActivity using the Menu, Sign them out.
    
3. **Firebase Realtime Database**:
    - Add the `Realtime Database` **dependency** to your project.
    - Edit the `User` Class as needed to work with the database.
    - In the `create_user` function, when the task is **successful**:
        - Add the user signed up (email, name & password) using their `Uid` to the Database under the **Reference Users**.
    - Get **all the users** from the database and add them to the `ArrayList` and display them in the `ListView`.


##### Call an Instructor/TA to check your completed tasks

### Bonus:
    
1. Continuing the ListView Bonus:
    - Figure out how to have a profile picture saved in the Realtime Database! 

 
###### make sure you commit and push your code.

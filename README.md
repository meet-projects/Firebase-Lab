# Firebase Lab

## Objective: 
In this lab, you will learn how to implement ListView in your Android Studio apps and understanding how the Adapter works!  

By the end of this lab, you will have a custom ListView displaying all your users.  

## Instructions:

In this lab, you will continue from the previous labs and you will be adding a User ListView to your app!  

1. User class:
    - Open a Java file for your `User` class.
    - Add the following attributes to your class:
      - Name.
      - Email.
      - Password.
      - you can add any **additional attributes** you want.
    - Using **generate**, add a constructor, setters, getters and a toString.


2. `ListView` in XML:
    - Add a `ListView` component to your activity's XML file.
    - Open an XML file for the **custom row** in the layout folder and design it, should at least include:
        - Name.
        - Email


3. Creating an ArrayAdapter: 
    - Create a new class named `UserArrayAdapter`.
    - Copy the [ClassNameArrayAdapter](https://docs.google.com/document/d/148VUAErpZurx5NGTrQZ2Vxm_GZXy7Mt39oZ5b2plvAo/edit) template. Make sure to replace your class name instead of ClassName.
    - Get the user object using `getItem()`:
      - Make sure that the object is not null.
    - Get the Views from the custom_row and set the values according to the user objects.


4. In the Activity's Java file:
    - Create a user `ArrayList` and add objects to the list.
    - Initialize the `ListView` and find it through its id.
    - Initialize the `ArrayAdapter` and create an adapter object using your custom Adapter.
    - Set the ListView adapter to the one you made.


##### Call an Instructor/TA to check your completed tasks

### Bonus:

1. Make the items clickable:
    - If we click on an item in the list, a new page will be opened:
    - The new page will show the name of the user we clicked on. 
    
2. Let’s add a profile image:
    - Add an src attribute to your User class (should be String). 
    - Add a rounded image component to the layout we prepared for our rows. 

 
###### make sure you commit and push your code.

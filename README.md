# Authorization app

Pet-project for learning in JavaFX and MySQL.

It was originally a console application with writing to and reading from a .txt file to check attributes. Boring? Yes! Now I have added a graphical interface and write-read to the database.

You can authorize and save your data in the database, and then make a successful authorization.
The project uses: 
- SDK: openjdk-18;
- language level 11;
- MySQL database 8.0.28 (connection via Connector/J );
- javafx-sdk-18.
- scenes in .fxml files created in SceneBuilder.

***When writing the code, lambda expressions were actively used, which made it possible to significantly reduce the number of lines and increase readability.***

Database queries are generated by the singUpUser() and getUser() methods in the DatabaseHandler class.

This is an open project and you can copy and use the code for your own purposes.
***

### You can check out the demo below:

![bandicam 05](https://user-images.githubusercontent.com/91153388/163765884-2e5ad91d-64e1-49e4-a652-2d7827114639.gif)

Pressing the "Back" button returns you to the previous window.

If you enter erroneous data or leave the login and password fields empty, you will receive an error message.

There are checks of fields for entering data when registering a new user (it is impossible to register without filling in all the fields and with a password shorter than 6 characters).
***
*You can find my contacts in my profile.*

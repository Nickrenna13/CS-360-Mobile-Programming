# CS-360-Mobile-Programming
# Inventory Management
# Requirements and goals:
The requirements for the Inventory management mobile applications were to implement a login feature where the user can register login credentials, and then use those credentials to login to the app. The application checks the username and password and compares it against information stored in a database while the user is logging in. The next requirements are to allow users to create inventory items and add them into the database and the user can then view these changes on the main screen. The user can also delete inventory and update inventory items UPCs, descriptions, quantities and types and the database will reflect those changes in the mobile inventory application. The last requirement was prompting the users for permission to send SMS messaging notifications about low inventory quantities. One goal I wanted to implement is having one screen that allows the user to interact with their inventory such as add, edit, or remove inventory all in one screen. 
# User needs:
The application starts out in a home screen where the user will select a login button and from the user can login if they have an account already or select a register button which will allow the user to create credentials which are stored in a database. After the user creates login information, they will be directed to the main screen that supports viewing, adding, editing, and removing inventory all in one screen. The screens and features included allow the user to focus on their job tasks and update their inventory quickly as they work. Also, a setting button allows the user to quickly enable or disable the SMS messaging system and the application will still be functional for either decision.  In the future if more permissions were to be implement the setting button would be a great location to store user settings selections. 
# Coding Process:
For the coding process I started out with creating the database for the user and then implementing the login and register activities to function correctly. I spent one day working on the login logic and researching different ways I could implement all required aspects on logging in. Some of the developing and testing for the login feature was trial and error and trying different implementations to find the best fit for the application. One strategy I used was using a checklist sheet for each requirement and goal and this allowed me to stay organized.   
# Testing:
I tested the Inventory application using the Android Studio emulator and three different mobile devices. The first virtual mobile device was a tablet because my thinking was that the user in a warehouse setting or similar might be using a bigger screen, so I tested all the features and looks with this device first. The rest of the mobile devices were put through the same testing to ensure the features and looks are correct. 
For the login process I needed to make sure the user could register and then login with the information they provide in the register screen. Another test was to ensure that the user could login after the device was shut down meaning that the database is persistent and database tables hold the user information. Testing to ensure the inventory contents are still present in application when the device is turned off was tested with the three devices. The use of tables in the database to hold UPC numbers, item descriptions, item quantity and item type. The testing process is important to ensure that the application behavior in the correct way and to ensure that the user can use the application to manage their inventory. 
# Overcoming Challenges:
My biggest challenge was having the inventory app to populate the inventory into the main screen, so the user can read, edit, add, or remove their inventory. After doing some research I created a base adapter from an android website and function in a java file that would connect to the database to show inventory items and then update the adapter to show the inventory. 
# Number One Component:
The creation of the UI was the most successful component of the application. Hooking up the database was a challenge but overall, I found the creation of the UI to be the better component created. I was able to demonstrate the knowledge learned from the course by applying best practices for Android applications.  
# Screenshots 
Home Screen
![image](https://github.com/Nickrenna13/CS-360-Mobile-Programming/assets/115961576/9121f4df-0dfe-4810-a0f4-62c680010b70)
Login
![image](https://github.com/Nickrenna13/CS-360-Mobile-Programming/assets/115961576/55386086-93cf-4234-8f20-539e5b0c6ec3)
Register
![image](https://github.com/Nickrenna13/CS-360-Mobile-Programming/assets/115961576/ccf91ba3-8d5e-4fed-9081-73f596c64660)
Inventory Screen
![image](https://github.com/Nickrenna13/CS-360-Mobile-Programming/assets/115961576/a3b1f249-8efa-47a3-b4a8-4779fb1d67ce)
SMS messaging Screen
![image](https://github.com/Nickrenna13/CS-360-Mobile-Programming/assets/115961576/0d820f14-659e-40b3-a7aa-9e490c81f533)
Add Inventory 
![image](https://github.com/Nickrenna13/CS-360-Mobile-Programming/assets/115961576/fd149d73-f2f9-4279-b3d7-9516c4a88da3)
Editing pop up window
![image](https://github.com/Nickrenna13/CS-360-Mobile-Programming/assets/115961576/2b2ed868-1b89-488f-b4d0-cb9bc7f6791d)










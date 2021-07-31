# MobileAppFinal
Project Summary  
Our group is creating an Inventory Management app in Java. The goal of the project is to have an application where a business could track and manage their inventory efficiently and have everything conveniently located in one place. An administrator user will be put in place who can manage the inventory and manipulate items when needed. There will be users without the same administrative rights which are used for employees to track inventory. The purpose of this is for security and to make sure the employee is not able to fabricate or falsify the inventory. The plan is to get rid of manually tracking inventory and being able to track it all through an application. We will have a feature where you can scan each barcode and it will fill in the information of the product using the UPC barcode.
Splash Page  
Home Page  
Login  
Registration Page  
Barcode Scanner / Add Items  
Inventory/Admin  
Delete Section  
Settings - Logout Option  

Demo Link: https://youtu.be/a9mpZ66oDzM  

# Instructions to Start the App:
Download or clone the repository locally onto your hardrive
Wait for the files to load into directory
Change file path with the name of your User folder, not mine. (i.e. C:// Users/kash/Documents/messageboardappproj/)
Build the project
After it is build, type this command into your terminal "firebase emulators:start --project=demo-friendlychat" (you will be able to see realtime database)
The command above will use the firbase.json file and start the emulator and will give you a local port whjich you can access the firebase emulator (see status or authentication, cloud messaging, etc.) Once cloned, you should be able to press the play button or go on the "Run" tab on the tool bar and press run 'build-android.app'
** make sure your gradle is 6.7.1 or change it in the gradle-wrapper.properties to 6.7.1. I had to move the gradle-wrapper-properties file outside in the main Messageboard folder. **

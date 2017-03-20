# FoodMenu
This project module compose of a Client and Server which follows POX over HTTP standard. There is a REST based service which is consumed by a client using AJAX call for adding and fetching Food Item details. It also possess a Database feature by updating local file on file system.

# CONTENTS
I.	DELIVERABLES
II.	HOW TO EXECUTE
III.	MINIMUM SYSTEM REQUIREMENTS
IV.	FEEDBACK & UPDATES 

# HOW TO EXECUTE (BUILD and RUN)
Following steps need to be followed for building the project and executing it:
# Error Scenario
I.	UNZIP the shared file. Place the Input XML FILE with name (FoodItem.xml) at User Home Directory Path (like C:/Users/fCallis)
  <IMPORTANT-NOTE> If Input XML File is not placed at correct path, Web Server will start with blank database with no food Item added.    
  Also if File is not present at correct path, system will print error on Console where it will mention the correct path for User   
  Reference as below: Pic1 in shared in seperate screenshot Document
  
# FOR ECLIPSE:
II.	IMPORT PROJECT:  
  1.	SELECT FILE > IMPORT & SELECT MAVEN > EXISTING MAVEN PROJECT

  2.	SELECT THE UNZIPPED PROJECT FOLDER (POX-FoodMenu-vgaur1-Eclipse) and Click FINISH


  3.	Once project is downloaded, Update Maven Project:

  4.	Create a NEW APACHE TOMCAT SERVER AND CONFIGURE PROJECT ON IT:
    i.	FILE > NEW > Other …
    ii.	Select SERVER and Click NEXT
    iii.	Select TOMCAT v8.0 Server from given List
      a.	Server’s Host Name: localhost
      b.	Server Name: Tomcat v8.0 Server at localhost
      c.	Server runtime Env: Default (Apache Tomcat v8.0)
    iv.	Now Add Resource to Server:
  Select POX-FoodMenu-vgaur1-Eclipse > Add 


  5.	DEPLOY Project on SERVER: 
  FILE > RUN AS > RUN ON SERVER


  6.	REST CLIENT: Select any browser and go on following link:
  http://localhost:8080/POX-FoodMenu-vgaur1-Eclipse/UI#
  Provide appropriate FOOD ITEM API REQUEST
  And system will show FOOD ITEM API RESPONSE


  # IMPORTANT POINT:
  Webservice is built to listen on 8080 PORT. IF PORT NUMBER is changed in CLIENT/SERVER, program would not execute as expected and in 
  that scenario, Port number need to be changed to 8080.
  
  # MINIMUM SYSTEM REQUIREMENTS [PART III]
    Eclipse Mars (4.5.1) 
    Tomcat 8.0.30 with Eclipse
    Window 7 (32/64 Bit)




# WebLevi
  It is a web application built with Java that demonstrates the simple CRUD opertations and user search function. 
  

  To see **WebLevi** live in action, open a browser tab and go to  https://web-application-project-dwit.herokuapp.com/. 
  


## How to run the app on localhost
   
   1. Install intellij 2021 ultimate edition and XAMMP.  
   2. Clone the project into your desired directory.
   3. Open the project with intellij.
   4. You need to add External libraries such as MySQL connector and JavaServer Pages Standard Tag Library(JSTL).
     * You can download JSTL from https://tomcat.apache.org/taglibs/standard/ and MySQL connector from https://dev.mysql.com/downloads/connector/j/.
     * After the files are downloaded you need to place both jar files inside the lib directory of both tomcat and intellij.
     * Then, open intellij and go to file and click on project structure.
     * Click on the libraries tab and then on plus sign located in the top-middle of the tab and select java.
       <p align="center" width="100%">
         <img src="https://user-images.githubusercontent.com/41668152/161547728-29ca211d-676a-411d-ac39-ed50c0415be3.png" width="200" height="200">
       </p>
   
     * From then, you can add the two libraries that you downloaded and placed in the tomcat lib directory.   
        <p align="center" width="100%">
         <img src="https://user-images.githubusercontent.com/41668152/161548080-17863cbd-ec2e-4703-a55a-51b700341f82.png" width="200" height="200">
        </p>
   5. Open XAMMP control panel and then, Run MySQL and Apcahe services.
   6. Configure the tomcat server in the edit configurations of intellij.
     ![image](https://user-images.githubusercontent.com/41668152/161539448-3fb71b67-0bba-4a7f-b0f3-7a56fff816a7.png)
   7. Then, click on the configure button as shown in the picture below.
     ![image](https://user-images.githubusercontent.com/41668152/161539767-d2cb65a4-eaee-4a0c-8231-e4fd83824a9c.png)
   8. After, that you need to configure the home and base directory of the tomcat server which can be found inside the XAMMP folder.
     ![image](https://user-images.githubusercontent.com/41668152/161540124-6d5846ab-043c-451e-ab8c-9ecc3aae25ee.png)

## User Stories
   1. A user can add other users.
   2. A user can view other user details
   3. A user can update details of other users.
   4. A user can delete other users.
  
## Technical
   * The front end of the app is built with HTML/CSS, Javascript and Bootstrap 4.
   * The back end is built with JAVA EE 8 and it uses XAMMP with MySQL as a database. 
   * 
  
   2. 
    To get to dashboard, you must first register and then login.
  

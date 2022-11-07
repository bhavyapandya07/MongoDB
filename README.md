# MongoDB

<p align="left">
  I have added some MongoDB commands for the Database, I will add more commands as i Learn more and more in Mongo, will even add some API which i am currently working on REST API.
The List has not been update in the txt file, soon will add more new commands, till than you can work on the commands given by me.
  </p>
  
______________________________________________________________________________________________________________________________________________________________________
## Installation steps

1. Download MongoDB from this website and make sure you download the community version and not the enterprise version as shown in the image.
<br>https://www.mongodb.com/try/download/community
<br>![image](https://user-images.githubusercontent.com/80274814/200130863-44666f67-21f6-4376-8a99-3b9e8fd801fd.png)
  
2. Install MongoDB as a service in your device so it will be always running in the background and you dont have to start everytime from the app.
<br>![image](https://user-images.githubusercontent.com/80274814/200130996-b150409c-590d-4dc4-87bb-c6de96a70f9b.png)
<br>Here the Data directory can be change as per your way, in any folder.

3. Then after the install, Close MongoDB and MongoDb Compasss.
   1. go to the install Directory as shown mine, yours might also be same if you installed in the C drive.
   2. C:\Program Files\MongoDB\Server\6.0\bin
   3. copy this path.
   4. do Win+S type ENV and enter to System Environment Variables.
   5. tap on path and tap edit.
   6. in that add new path which we copied on the point ii and apply changes or OK.

4. Then open your Terminal/Windows PowerShell and type this command shown in the image.
<br>![image](https://user-images.githubusercontent.com/80274814/200131192-78b8c5c5-08fc-411a-89f3-a55b8e7393aa.png)

5. if this doesn't work or shows any error, then just do this things.
   1. go and download this zip file.
   2. https://www.mongodb.com/try/download/shell
   3. This is the MongoDB Shell or you can called it as the Compiler for Mongo. ![image](https://user-images.githubusercontent.com/80274814/200131550-054a319c-aef8-4732-b46c-0e1ca0c7b21e.png)
   4. Extract this Zip and in this zip go and copy this Mongosh.exe. ![image](https://user-images.githubusercontent.com/80274814/200131727-f14ce1e3-fc7a-44eb-bd0f-d7d730052e81.png)
   5. Then go and paste this exe in and MongoDB directory, for mine is this C:\Program Files\MongoDB\Server\6.0\bin (here i have just renamed the Mongosh.exe file into Mongo so it will be easy to type in the Powershell). ![image](https://user-images.githubusercontent.com/80274814/200131826-41fd3691-bd0d-4735-9e49-a809a85f5bb0.png)
   6. Add this path in the C folder where Mongo is installed C:\data\db.
   7. After this you can again go to the Terminal/PowerShell and type Mongo or Mongosh to start the Database.

_______________________________________________________________________________________________________________________________________________________________________
## Creating a Database 

1. Open MongoDB Compass and tap on Fill in Connection Fields individually. ![image](https://user-images.githubusercontent.com/80274814/200131983-d3a8cb19-a370-4380-97fb-a39edd83219b.png)
2. After this Screen will be shown then do nothing just tap connect. ![image](https://user-images.githubusercontent.com/80274814/200132026-6d92aac8-1d87-4fc4-8fc8-e5663f628fee.png)
3. Then Tap on Create Database. ![image](https://user-images.githubusercontent.com/80274814/200132060-c56287aa-ec8b-4fca-8bf2-0bd6c27872bf.png)
4. Name your Database according to you and add a collection name to it whatever you want, do tick any options just fill this 2 cells and tap Create Database.
5. This type of a Screen will be shown after the creation of database. ![image](https://user-images.githubusercontent.com/80274814/200132154-ba5c1191-9db0-4b3f-a1a4-cac461382c4c.png)
6. You can tap on the Database and Check Collection. ![image](https://user-images.githubusercontent.com/80274814/200132212-888da42d-8e36-4b31-8937-f53163519e7b.png)
7. Now Everything is set, Start Entering your data in your own database From the PowerShell.

_______________________________________________________________________________________________________________________________________________________________________
## All the powershell commands are given in the .txt file
you can also reffer to this links for understanding the commands
1. https://www.tutorialspoint.com/mongodb/index.htm
2. https://www.javatpoint.com/mongodb-tutorial

<br>also remember this things given in the image
<br>![unknown](https://user-images.githubusercontent.com/80274814/200244677-7a3729dc-e67a-4824-b169-e4b3bb445bec.png)
<br>![unknown (1)](https://user-images.githubusercontent.com/80274814/200244746-bacb0d3b-630b-4c03-b0cc-e64e5419cd6e.png)

_______________________________________________________________________________________________________________________________________________________________________






 


# demo-java-web-spring5-was9
Project demo Java + Spring 5 + Spring MVC deployed to WAS Websphere App Server 9

## Requirements
1. Eclipse version 2020-06 with plugin of WAS 9 
2. JDK 8 installed
3. App Server WAS 9 installed


## Settings in Eclipse
1. Set the next line in the file .ini of Eclipse path before --launcher.appendVmargs:
-vm 
C:\Program Files\IBM\WebSphere\AppServer\java\8.0\bin\javaw.exe
2. Run Eclipse as Administrator
3. Create new server WAS as name WAS9
4. Configure path Maven in Eclipse > Windows > Preferences > Maven > Installation > Add 

## Run Project
1. Import both projecs in Eclipse as "Existing projects into Workspace"
2. Run project with WAS9 as target server runtime
3. Go to test: http://localhost:9080/demo-java-web-spring5-was9/


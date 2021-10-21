# Taxi Service
This program imitates the work of taxi service.
### Tecnologies
JDBC, Servlet's, MySQL, Tomcat. 
## Let's install some programs:
- Install Tomcat [9.0.50](https://tomcat.apache.org/download-90.cgi) 
. Don't recommend installing version 10+ because program may not work correctly.
- Install [mySQL workbench](https://dev.mysql.com/downloads/workbench/).
### Configure your DB:
In resources you can find `init_db.sql`, copy sql query and paste to mySQL.
 This query creates schema and tables for this project.
## Run application:
Before you get access to all program functional you must authenticate.
- You can register(add) new User(Driver) `/drivers/add`
- After register, you need to login `/login`
#### All functional
- add new Driver  `/drivers/add`
- delete Driver  `/drivers/delete`
- show all Drivers `/drivers/`
- get all my Cars `/cars/my`
- add new Car `/cars/add`
- delete Car `/cars/delete`
- get all Cars `/cars/all`
- add driver `/cars/drivers/add`
- add manufacturer `/manufacturers/add`
- delete manufacturer `/manufacturers/delete`
- get all manufacturers `/manufacturers/all`
### Login page:
![img.png](src/main/resources/pictures/img.png)
### Main page:
![img_1.png](src/main/resources/pictures/img_1.png)




  

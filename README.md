# SpartaAcademyManagementSystem

Spring boot application which allows users to manage the trainers/trainees of Sparta Global.

# Description
**Trainers**
* Register new trainers 
* View a list of trainers

**Trainees**
* Register new trainees
* View a list of trainees

**Courses**
* View a list of avaliable courses on offer
* Register a new course
**Modules**
* View a list of modules that are taught 
* Register a new module
**Classroom**
* View a list of classrooms and their capacitys 
* Register a new classroom
**Groups**
* Register a new group and assign it trainees/trainers
* Allocate a group to a classroom and assign it with a schedule (ie. start date and end dates)

### Prerequisites
The web application utilises a local MySQL database to store the entered data.
I recommend MySQL workbench -
* MySQL Installer (MySQL Workbench, MySQL Server)- https://dev.mysql.com/downloads/installer/ 

* You'll need to specify the corresponding MySQL (local) database details into the "application.properties" file in order to succefully connect the application with the database.

## Built With
* [Spring Boot](https://spring.io/projects/spring-boot) - Platform based on Spring which provides a pre-defined web application development enviroment
* [Maven](https://maven.apache.org/) - Dependency Management


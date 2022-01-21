# AccesingDataMySQL
#Accesing to mysql, create only database db_example but not table
#mysql> create database db_example; -- Creates the new database
#mysql> create user 'springuser'@'%' identified by 'ThePassword'; -- Creates the user
#mysql> grant all on db_example.* to 'springuser'@'%'; -- Gives all privileges to the new user on the newly created database
#Click Dependencies in Spring Initializer and select Spring Web, Spring Data JPA, and MySQL Driver.
#The following curl command adds a user:
#$ curl localhost:8080/demo/add -d name=First -d email=someemail@someemailprovider.com
#The following command shows all the users:$ curl 'localhost:8080/demo/all'

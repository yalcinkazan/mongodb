# mongodb
Spring Boot MongoDB Microservice

# Prerequisites
MongoDB installed in your machine
</br>

# MongoDB Codes:

mongo </br>

use user </br>

db.user.find( {} ) -> To select all inserts in user database </br>
   
 # Service Usage:
 
 # Post 'http://localhost:8080/user'
 -JSON Content; </br>
{ </br>
    "firstName": "John", </br>
    "lastName": "Frusciante" </br>
} </br>

# Update 'http://localhost:8080/user/{id}'
 -JSON Content; </br>
{ </br>
    "firstName": "Jimi", </br>
    "lastName": "Hendrix" </br>
} </br>

# Delete 'http://localhost:8080/user/{id}'
# Get 'http://localhost:8080/user/{id}'
# Get All 'http://localhost:8080/user'

 

   
 
                                       

   

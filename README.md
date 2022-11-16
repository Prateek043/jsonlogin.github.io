# *Login2Xplore---JsonDB-Project*
A small project to demonstrate the new technology - JsonDB.

### :warning: *Warning !* ## 
*Since the api uses Http-connection (and not Https) and all the webhosting servers only allow Https connections.
So, This site faces the issue of sending and retrieving data. This issue will be resolved as soon the developers provide a secure-connection to API.
Although the illustrations are provided on the complete process.
But still if anyone wants to check this beautifully constructed page, Welcome !*

__Hosted Site link__  :  https://login2xplore-project.herokuapp.com/index.html    

## *Introduction*
    -This is a simple and elegant HTML,CSS,Js/jQuery Login/SignUp Page,
              to demonstrate the data sending & request handling over JsonPoweredDB-api for database management.
    -This project uses JsonPoweredDB for the backend usage of saving all users data in the Json-format.
    -Being the most efficient database, the time taken to POST & GET user-data from the database is almost null.
    -Unlike SQL and relational databases, this JsonPoweredDB feels user and developer friendly.
    
## *Easiest Syntax Usage :*
    
    // GET - Query
    
    {
    "token": "2134770734|19056227XXXXX281054|2134XXXXXX",
    "cmd": "GET",
    "dbName": "Company",
    "rel": "Employee",
    "jsonStr":{
        "empName": "Prateek kumar"
        }
    }
    
    // INSERT - Query
    
    {
      "token" : "90935402|-31948797XXXX293566|909XXXX",
      "cmd" : "PUT",
      "dbName" : "Emloyee",
      "rel" : "Emp-rel",
      "jsonStr" : {
        "name" : "prateek",
        "email" : "prateek@gmail.com",
        "mobile" : 7018516XXX,
        "address" : "Newyork"
            }
    }
    
*If there is no Database named - 'Employee', It will automatically create Database with the name without forcing developers to write code or throwing hundreds of errors.*

## *Benefits of using JsonPowerDB*
    -Proprietary algorithm for High Performance CRUD operations. Multiple times faster than popular DBMS.
    -Serverless support for faster development - A UI developer can develop complete dynamic application.
    -DBMS with built in web / application server and embedded caching makes the performance lightning fast.
    -Server side Native NoSQL - best query performance.
    -In-built support to query on multiple JPDB databases.
    -Multi-mode DBMS - Document DB, Key-Value DB, RDBMS support.
    -Schema free - easy to develop and maintain.
    -Web-services API - Can be used with any programming language that has support for HTTP.

## Release History
*Originally developed by Prateek kumar,Student of Bangalore institute of Technology,
                          for the demonstration of JsonPoweredDB on Nov-15,2021. 
    -This project is a testimony of the course provided by Login2Xplore Company, 
     that demonstrates the usage and functionality of Json-Powered Database. 
    -The date of submission of this project was by Nov-16,2021.* 

## Sources

*CodePen.io , Youtube.com, SweetAlert.js.org, BootStrap and jQuery for Frontend.*

*Login2Xplore Documentation link for Backend & Miscellaneous Query-Reference* : http://login2explore.com/jpdb/index.html#introduction-jpdb

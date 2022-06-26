SpringBootApplication

This is a spring-based Application that allows CRUD operations on connection from multiple databases via different sources i.e. MongoDb and Sql database

Once the PUT request is sent via Postman it adds the data to their alloted data source
On sending the GET request it fetches and show the data from the database

Sample Data: { "firstName":"Rahul", "lastName":"Sharma", "email":"rahul@xyz.com",

"courses":[ { "name":"math", "description":"Mathematics", "email":"" }, { "name":"sci", "description":"Science", "email":"sci@abc.com" } ]

}

Here the main data of the student is stored in an SQl database whereas the course data in the mongoDb collection.

Similarly data can be added, deleted and updated in both the databases from a single application.

**MongoDb is hosted on localhost. **To check connection with Sql please create your own database and alter the username and password in the Application properties file

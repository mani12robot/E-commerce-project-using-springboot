<a href="https://trendshift.io/repositories/151" target="_blank"><img src="https://trendshift.io/api/badge/repositories/151" alt="jaygajera17%2FE-commerce-project-springBoot | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

## New Version ( what's new)
- Hibernate configuration added( database and tables automatically create when run the project)
- Service classes provide reusable services throughout project
- dao classes interact with database 
- bug fixed ( product image, security , etc..)
- support in both eclipse & intellij ide
- overall redesign entire code that help reusability. 
- disclaimer: currently working on this branch so there may be some bug related to endpoint, and working on cart logic.
  
## Quickstart

1. Clone the repository
2. Open the project in your IDE: IntelliJ IDEA (recommended) or Eclipse
3. Make sure you are in the `JtProject` directory
4. Configure the database connection in `application.properties` file
5. Run the project (by running the `main` method in `JtSpringProjectApplication.java`)
6. Open http://localhost:8080/ in your browser!
   * If you ran the `basedata.sql` script, you can log in with the following credentials as admin:
     * Username: `admin`
     * Password: `123`
   * Log in as a normal user:
     * Username: `lisa`
     * Password: `765`

### Database

MySQL or MariaDB can be used. The connection is configured in:

`src/main/resources/application.properties`

```properties
db.url=jdbc:mysql://[ip]:[port]/ecommjava?createDatabaseIfNotExist=true
db.username=[username]
db.password=[password]

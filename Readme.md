 
# Asset token project 🏢💰🔒

This project consists of tokenizing real life assets.
Allows the user to buy and sell tokens of projects created on the ethereum blockchain


### Requirements

- Database MySQL version 8 or later.
- Maven version 3 or later.
- JDK version 1.8.
- Git.


### Configuration

- Clone project. 
```
git clone https://github.com/javimayer14/asset-token-api.git
```
- The IDE used to view the code must have the lombok tool installed
```
https://projectlombok.org/download
```
- A MySQL database must be created.
- To facilitate the creation of the DB it is recommended to create a container as follows
```
sudo docker run --name asset_token_db -e MYSQL_ROOT_PASSWORD=token -e MYSQL_USER=token -e MYSQL_PASSWORD=token -e MYSQL_DATABASE=asset_token_db -p 3306:3306  -d mysql:8
```

- Position yourself in the project directory and run `` `mvn clean install``` from a terminal to compile the project.

### Execution
- Position yourself in the project directory and run ```mvn spring-boot:run``` from a terminal.
- You can also run the application from your preferred ide.


```markdown
# Mission Reflection

Writing a docker-compose.yml file makes a cloud engineer's job easier because the configuration for the application can be written in one file. Instead of manually typing commands for each container, the engineer can use Docker Compose to deploy the services together. This makes the deployment process more organized and easier to repeat.

An indentation error in a YAML file can cause problems because YAML depends on proper spacing and indentation. For example, using a Tab instead of Spaces can make the configuration invalid. Because of this, Docker Compose may not be able to read the file correctly or start the services.

We used environment variables such as MYSQL_PASSWORD to provide the required database settings to the containers. These variables allow the Nextcloud application and MariaDB database to use the needed configuration from the Compose file. They also keep the settings organized within the deployment configuration.

It felt convenient to deploy a fully functional enterprise cloud storage system in just a few minutes because Nextcloud and MariaDB could be deployed together using Docker Compose. Instead of setting up each part manually, the Compose file contained the configuration needed for the services. Seeing the Nextcloud installation page in the browser also showed that the containers were working together.

Since Mission 1, my understanding of Cloud Computing has evolved because I have learned more about how cloud environments can be planned, deployed, and managed. I learned that Cloud Computing is not only about online storage or servers, but also involves infrastructure, containers, services, automation, and documentation. This mission helped me understand how Infrastructure as Code can make cloud deployment more organized and repeatable.

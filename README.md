# Spring microservice library configuration server

* This service is part of the simple library microservices project and includes
  * [library configuration server](https://github.com/maurofokker/spring-microservices-library-config)
  * [library reservation](https://github.com/maurofokker/spring-microservices-library-reservation)
  * [library catalog](https://github.com/maurofokker/spring-microservices-library-catalog)
* Microservices reference can be found [here](https://github.com/maurofokker/microservices-demo)

* Create a centralized config repository in git
  * for this case a _configuration_ folder is created in project workspace (`./workspace/microservices/library/configuration`)
  * initialize git repository with `git init` command
  * add configuration files
    * `catalog-default.properties`
      ```properties
        catalog.size=3
      ```
    * `config-client-default.properties`
      ```properties
        message=This is the default
      ```
    * `config-client-development.properties`
      ```properties
        message={cipher}dee7458e426ca9015159617b8e9aceef814877bf58496264c49a75a069ed8c3e
      ```
  * add files to stage and commit them

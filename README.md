React Assets Maven Plugin Sample
=======================

This sample project shows how to use [React Assets Maven Plugin](https://github.com/maasdi/react-assets-maven-plugin), 
this project use spring-boot and Thymeleaf, but the plugin should work with any Maven Project.

Refer to `pom.xml` to see how it's done.

## How to run
* Just `./mvnw spring-boot:run` maven will run `npm install && npm run build`, copy react build assets to `${project.build.directory}/classes/public/`, process `${project.basedir}/src/main/resources/templates/home.html` and start the application
* Open `http://localhost:8080/home` the page is render correctly with correct react assets
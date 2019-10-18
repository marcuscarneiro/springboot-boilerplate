# My Spring Boot Boilerplate

Personal Spring Boot boilerplate containing (for now) the following dependencies:
- Spring Web
- Spring Security
- Spring Data JPA
- H2 Database
- Thymeleaf

## Instructions

First, import this **maven** project in your prefered IDE;

For development purposes only, you may use a self-signed SSL certificate.
You can create one localy running the following command (windows):

```sh
C:\Program Files\Java\jdk1.8***\bin>.\keytool -genkey -alias myssl -storetype PKCS12 -keyalg RSA -keysize 2048 -keystore myssl.p12 -validity 3650
```
Answer the prompted questions;

Copy the generated myssl.p12 file to the src/main/resources folder;

Configure the application.properties with the informations you previously provided;

That's it! Hit the IDE run button and begin to work.

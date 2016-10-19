# Termed WAR

Termed is a web-based vocabulary and metadata editor. 

Termed WAR builds a single war composing of Termed API and UI.

## Building

First install [Termed API](https://github.com/THLfi/termed-api) and [Termed UI](https://github.com/THLfi/termed-ui) (e.g. download or clone projects and run `mvn install` on both). Then run `mvn install` on this project. This produces a war file `/termed-war/target/termed.war`.

## Deploy

Drop termed.war into servlet container (e.g. Tomcat).

External properties can be configured using standard mechanisms provided by spring boot:
http://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-external-config.html

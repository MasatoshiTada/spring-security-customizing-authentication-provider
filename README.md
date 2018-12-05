Customizing Spring Security's AuthenticationProvider
====================================================

# How to try

## Run Authentication Server

```bash
$ cd authentication-server
$ mvn spring-boot:run
```

## Run Client

```bash
$ cd client
$ mvn spring-boot:run
```

> My implementation of `AuthenticationProvider` is [`MyAuthenticationProvider`](client/src/main/java/com/example/client/MyAuthenticationProvider.java).

## Using Web Browser
Access [http://localhost:8080/](http://localhost:8080/).

Correct credentials are username = "user" and password = "password".
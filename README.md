#spring-starter-1

## Building a Web Service using Spring the easy way

Some parts of this readme text are copied from the spring official guide website, but I also want you to directly dive into without the need to jump to other pages, but just for you here is the link:  https://spring.io/guides/gs/rest-service/ (also it's an reminder for me if I will need this later :p)

### What you’ll build
You’ll build a service that will accept HTTP GET requests at:
```
http://localhost:8080/greeting
```
and respond with a JSON representation of a greeting:
```json
{
    "id":1,
    "content":"Hello, World!"
}
```
You can customize the greeting with an optional name parameter in the query string:
```
http://localhost:8080/greeting?name=User
```
The name parameter value overrides the default value of "World" and is reflected in the response:
```json
{
    "id":1,
    "content":"Hello, User!"
}
```

### What you’ll need

- About 15 minutes
- A favorite text editor or IDE
- JDK 1.6 or later
- Gradle 1.11+ or Maven 3.0+
- You can also import the code from this guide as well as view the web page directly into Spring Tool Suite (STS) and work your way through it from there.

Just as sidenode: I used STS because it's really really nice ;)

### Install Gradle & Maven
Have a look if you already have Gradle / Maven set up on.
```
gradle -v & mvn --version
```
If you don't have this ready just use [Homebrew] by simply try to install gradle:
```
brew install gradle
```
And also maven:
```
brew install maven
```

[Homebrew]:https://github.com/Homebrew/homebrew


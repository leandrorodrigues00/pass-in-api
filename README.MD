# Pass.in - participant management in in-person events 🎟️

<br>

<p align="center">
  <a href="#-about-the-project">About the project</a> •
  <a href="#-technologies">Technologies</a> •
  <a href="#-Requirements">Requirements</a> •
  <a href="#-api-documentation">API Documentation</a> •
<a href="#-getting-started">Getting started</a> •
<a href="#-license">License</a>

</p>

## 👩‍💻 About the project

Pass-in is an application for managing participants in in-person events. The tool allows organizers to register events and open public registration pages. Registered participants can issue credentials to check in on the day of the event. The system scans participants' credentials to allow entry to the event.

## 🚀 Technologies

- [Java](https://www.java.com/)
- [Spring](https://spring.io/)
- [Lombok](https://projectlombok.org/)
- [HSQLDB (HyperSQL Database)](http://hsqldb.org/)
- [Flyway](https://flywaydb.org/)

## Functionalities Supported by the API

### Functional requirements

- The organizer must be able to register a new event;
- The organizer must be able to view data from an event;
- The organizer must be able to view the list of participants;
- The participant must be able to register for an event;
- The participant must be able to view their registration badge;
- The participant must be able to check-in at the event;

### Business rules

- The participant can only register for an event once;
- The participant can only register for events with available places;
- The participant can only check in to an event once;

### Non-functional requirements

- Check-in at the event will be carried out using a QRCode;


## 👩‍💻 API documentation

For API documentation, visit the link: https://nlw-unite-nodejs.onrender.com/docs


## 💻 Getting started

### Requirements

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) version 11 or higher.

### Running

**Clone the project and open it in your favorite IDE such as [Eclipse](https://www.eclipse.org/), [NetBeans](https://netbeans.apache.org/), or [IntelliJ IDEA](https://www.jetbrains.com/idea/)**

```bash
$ git clone https://github.com/leandrorodrigues00/pass-in-api && cd pass-in-api

# After opening the project in your IDE, locate the main class `PassInApplication.java` and run it to start the application server.

```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with 💜&nbsp; by  Leandro Rodrigues
</p>

## I’ve built a functional, full-stack web application using modern Java with Vaadin and Spring BooT.
  
The application is a customer relationship management (CRM) system for managing contacts. It features:

A log-in screen to restrict access.
A responsive layout with side navigation that works on desktop and mobile.
A database for persistent data storage.
A list view that can be sorted and filtered.
A form to edit and add contacts.
A dashboard view.

## Project structure

- `MainLayout.java` in `src/main/java` contains the navigation setup (i.e., the
  side/top bar and the main menu). This setup uses
  [App Layout](https://vaadin.com/components/vaadin-app-layout).
- `views` package in `src/main/java` contains the server-side Java views of your application.
- `views` folder in `frontend/` contains the client-side JavaScript views of your application.
- `themes` folder in `frontend/` contains the custom CSS styles.



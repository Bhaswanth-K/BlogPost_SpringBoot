# BlogPost

A simple Spring Boot blog application with user authentication (form-based and OAuth2 with Google/GitHub), blog CRUD operations, and an H2 database. The application allows public viewing of blogs, with authentication required for creating, updating, or deleting posts.

## Features
- **Public Blog Viewing**: Access `/blogs` and view individual blogs without login.
- **User Authentication**:
  - Form-based login/registration.
  - OAuth2 login with Google and GitHub.
- **Blog CRUD**: Create, update, and delete blog posts (authenticated users only).
- **H2 Database**: File-based persistence with H2 console for DB management.

## application.properties:
For application properties, see [`src/main/resources/application.properties`](src/main/resources/application.properties).


# Rust_Web_Full_Stack_Project
## Overview

This Rust-based web development project combines backend and frontend components, emphasizing the construction of a RESTful API server. The tutorial covers various functionalities, including TCP server setup, HTTP handling, Actix-Web integration, database operations with sqlx and PostgreSQL, error handling, and server improvements. The project also explores frontend development using both traditional server-side rendering (SSR) and WebAssembly (Wasm), all implemented exclusively in the Rust programming language.

## Backend Development

### Core Features

- **TCP Server and HTTP Handling:** Constructed a basic TCP server, implemented HTTP request and response handling, and established the foundation for Router, Server, and Handler components.
- **Actix-Web Integration:** Developed a foundational server using the Actix-Web framework.
- **RESTful API Server:** Created a REST API server with features such as health checks, course addition, and various query functionalities. Data is stored in memory.
- **Database Integration with sqlx:** Utilized sqlx to query data from the 'Course' table in the database.
- **PostgreSQL Database Integration:** Continued SQL queries on the 'Course' table in the database and replaced the data source with a PostgreSQL database.
- **Error Handling:** Implemented error handling mechanisms to enhance server reliability.
- **Server Improvement with PostgreSQL:** Enhanced the existing server, focusing on PostgreSQL DB knowledge.

## Frontend Development

### Core Technology

- **WebAssembly (Wasm) and Server-Side Rendering (SSR):** Implemented both traditional SSR for web applications and WebAssembly for enhanced frontend capabilities.

### Language

- Entirely implemented in the Rust programming language.

## Technical Implementation

- Detailed implementation instructions for each component are available within the project structure.

## Technical Summary

- **Backend:** Actix-Web framework, TCP server, RESTful API development, database integration with sqlx and PostgreSQL.
- **Frontend:** Server-side rendering (SSR), WebAssembly (Wasm), Rust language for both frontend and backend.

## Getting Started

- Follow the provided instructions for each component to gain a comprehensive understanding of the project.

## Note

- For a cohesive learning experience, it is recommended to explore the project in its entirety.
- Frontend and backend components are tightly integrated, providing a holistic perspective on web development in Rust.

## File Tree

```
|
├───db
│   └───src
├───s1
│   ├───http
│   │   └───src
│   ├───httpserver
│   │   ├───data
│   │   ├───public
│   │   └───src
│   ├───src
│   ├───tcpclient
│   │   └───src
│   └───tcpserver
│       └───src
└───ws
    ├───src
    └───webservice
        └───src
            ├───bin
            ├───db_access
            ├───handlers
            └───models
```

## Rust  Version

```
>> rustup --version

rustup 1.26.0 (5af9b9484 2023-04-05)
info: This is the version for the rustup toolchain manager, not the rustc compiler.
info: The currently active `rustc` version is `rustc 1.75.0 (82e1608df 2023-12-21)`
```

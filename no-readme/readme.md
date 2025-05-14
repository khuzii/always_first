# Compact Disc Catalog Application

## Introduction

The Compact Disc Catalog Application is a Spring Boot-based RESTful web application that provides a catalog of compact discs (CDs). It allows users to perform CRUD (Create, Read, Update, Delete) operations on CDs and their associated tracks. The application uses a MySQL database for data persistence and integrates Swagger for API documentation.

## Features

- RESTful API for managing CDs and their tracks.
- CRUD operations for CDs.
- MySQL database integration for data storage.
- Swagger UI for API documentation and testing.
- Frontend pages for interacting with the API using AJAX and jQuery.
- Logging with Log4j2 for application events.

## Technologies Used

- **Backend**: Spring Boot, Spring Data JPA
- **Frontend**: HTML, CSS, JavaScript, jQuery, DataTables
- **Database**: MySQL
- **Logging**: Log4j2
- **API Documentation**: Swagger
- **Build Tool**: Maven

## Prerequisites

- Java 11 or higher
- Maven
- MySQL database
- (Optional) Docker for containerized deployment

## Setup Instructions

### Steps to Run Locally

1. **Clone the Repository**:
   ```sh
   git clone <repository-url>
   cd <repository-directory>
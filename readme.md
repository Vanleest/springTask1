# Spring Boot Hello Application

## About

This is a simple Spring Boot web application that demonstrates the use of controllers and Thymeleaf templates. It provides a basic example of how to pass data from the backend to a frontend template and render dynamic content based on user input.

---

## Features

1. **Home Page** (`/`)  
   Displays a simple static message:  
   **"Hello from spring controller."**

2. **Greeting Page** (`/greeting?name=<name>`)  
   Dynamically renders a personalized greeting message based on the `name` parameter.
    - Default: If no `name` is provided, it greets "World."
    - Example: `/greeting?name=Krzysiek` renders:  
      **"Hello, Krzysiek!"**

---

## Tech Stack

- **Language:** Java
- **Framework:** Spring Boot
- **Template Engine:** Thymeleaf

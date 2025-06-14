# Specification Sheet

## Project Name
Simple Actix Web Server

## Purpose
This project implements a basic HTTP server that responds with "Hello, World!" to GET requests on the root path (`/`). It serves as a minimal example of an `actix-web` application.

## Dependencies
- `actix-web`: A powerful, pragmatic, and extremely fast web framework for Rust.

## How to Build and Run
1. **Ensure Rust is installed:** If you don't have Rust, install it from [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).
2. **Clone the repository:**
   ```bash
   # git clone <repository-url>
   # cd <repository-name>
   ```
3. **Build the project:**
   ```bash
   cargo build
   ```
4. **Run the project:**
   ```bash
   cargo run
   ```
   The server will start on `127.0.0.1:8080`. You can access it by opening this address in your web browser or using a tool like `curl`.

## Endpoints
- **`GET /`**:
    - **Description**: Returns a plain text "Hello, World!" message.
    - **Response**:
        - Status Code: `200 OK`
        - Body: `Hello, World!`

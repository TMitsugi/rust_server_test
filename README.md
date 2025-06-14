# rust_server_test

This project is a simple web server written in Rust.

## Purpose

The main purpose of this project is to experiment with building web servers using the Rust programming language. It serves as a learning exercise and a basic template for more complex web applications.

## Building and Running the Project

To build and run the project, follow these steps:

1.  **Install Rust:** If you don't have Rust installed, download and install it from [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).
2.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd rust_server_test
    ```
3.  **Build the project:**
    ```bash
    cargo build
    ```
4.  **Run the server:**
    ```bash
    cargo run
    ```
    The server will start on `127.0.0.1:7878` by default.

## API Endpoints

The server currently has the following API endpoints:

*   **GET /**: Returns a simple "Hello, world!" message.
*   **GET /sleep**: Simulates a long-running process by sleeping for 5 seconds before returning a message.

This is a basic example, and more endpoints and features can be added in the future.

```mermaid
graph TD
    A[Start] --> B{HttpServer::new()};
    B --> C{App::new().service(hello)};
    C --> D{bind("127.0.0.1", 8080)?};
    D -- Ok --> E{run().await};
    D -- Err --> F[Return IO Error];
    E -- Ok --> G[Server Stops Gracefully];
    E -- Err --> F;
    G --> H[End];
    F --> H;
```

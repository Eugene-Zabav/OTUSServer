# Simple HTTP Server

This project is a simple HTTP server written in Python. It accepts HTTP requests, processes them, and sends back responses.

## Key Functions

- `handle_request(connection, address)`: This function handles HTTP requests. It takes a connection and an address as parameters. The request is parsed, and then a response is formed and sent.

- `main()`: This function creates the server socket, binds it to a specific host and port, and then starts listening for incoming connections. When a connection is established, it is passed to the `handle_request()` function for processing.

## Usage

To run the server, simply execute the Python script:

```bash
python main.py
```

The server will listen on 127.0.0.1 and a random port between 10000 and 20000. You will see connection and processing messages in the console.

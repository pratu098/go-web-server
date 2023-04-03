# Web Server in Go

This is a simple web server written in Go that responds to `./hello` and `/form` endpoints.

## Requirements

* [Go](https://golang.org/dl/) (version 1.16 or higher)

## Installation

1. Clone this repository:

        git clone https://github.com/pratu098/go-web-server.git

2. Install the dependencies:

        go mod download

3. Start the server:

        go run main.go

4. Open a web browser and navigate to http://localhost:8080

## Usage

### Hello Endpoint

Sending a GET request to http://localhost:8080/hello will return a response like this:

        Hello, World!


### Form Endpoint

Sending a GET request to http://localhost:8080/form will display a simple form that asks for a name and an address. Submitting the form will send a POST request to the server with the form data. The server will then display the name and address in the response.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

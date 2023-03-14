# PDF_Retriever

This is a simple Go program that allows you to download a file from a given URL and save it to the current working directory.

## Usage
To use this program, follow these steps:

- Clone the repository to your local machine.
- Navigate to the root directory of the project.
- Run go run main.go command in your terminal.
- Enter the name of the file you want to download with its extension and press enter.
- Enter the link of the file you want to download and press enter.
- The program will download the file and save it to the current working directory.

## Dependencies
This program uses the following third-party libraries:

- fmt: to format console output
- io: to copy bytes from the HTTP response body to the file
- log: to log errors to the console
- net/http: to send HTTP requests and receive responses
- os: to create and close the file

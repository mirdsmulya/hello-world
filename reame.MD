# Go Web Server

This is a simple Go web server that responds with a "Hello World" message.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need Go installed on your machine. You can download it from the [official website](https://golang.org/dl/).

### Installing

Clone the repository to your local machine:

```bash
git clone https://github.com/mirdsmulya/hello-world.git
cd yourprojectname
go build -o main .
```

### Using the Application

Once the server is running, you can navigate to http://localhost:5000 in your web browser. You should see a message saying "Hello World from Mirdan!".

The name "Mirdan" is retrieved from the NAME environment variable. If this variable is not set, the name defaults to "Mirdan".

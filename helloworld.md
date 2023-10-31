# Hello, World! in Go

In this tutorial, we'll guide you through creating a basic "Hello, World!" program in the Go programming language.

## Step 1: Set up your Go environment

Before you start, make sure you have Go installed on your system. You can download it from the [official Go website](https://golang.org/dl/). Follow the installation instructions provided.

## Step 2: Create a new Go file

Open your favorite text editor and create a new file named `hello.go`. The `.go` extension indicates that this is a Go source code file.

## Step 3: Write the "Hello, World!" program

Inside `hello.go`, enter the following code:

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
## Step 4: Understand the code

Let's break down what this code does:

- `package main`: Every Go program starts with a package declaration. The `main` package is special—it defines an executable program.

- `import "fmt"`: This line imports the `fmt` package, which contains functions for formatting input and output. It's part of the Go standard library.

- `func main() {...}`: This is the entry point of your program. When you execute the program, Go starts by running the `main` function.

- `fmt.Println("Hello, World!")`: This line uses the `Println` function from the `fmt` package to print "Hello, World!" to the console.



## Step 5: Run the program

Open a terminal or command prompt, navigate to the directory containing `hello.go`, and run the following command:

```bash
go run hello.go
```

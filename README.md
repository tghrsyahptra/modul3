# GoLang Hello World Example

This repository contains a simple Go program that prints "Hello, World!" to the console. It's a basic example to demonstrate the structure of a Go program and how to run it.

## Overview

The program consists of a single file `main.go` and includes the following key components:
- The `package main` statement, which defines the package for an executable program.
- The `import` statement, used to include necessary packages (in this case, `fmt`).
- The `main()` function, the entry point of any Go program.

## Code Explanation

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}

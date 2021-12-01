# Solution
https://exercism.org/tracks/go/exercises/hello-world/solutions/joelamalio

# Instructions

The classical introductory exercise. Just say "Hello, World!".

__"Hello, World!"__ is the traditional first program for beginning programming in a new language or environment.

The objectives are simple:

- Write a function that returns the string "Hello, World!".
- Run the test suite and make sure that it succeeds.
- Submit your solution and check it at the website.

If everything goes well, you will be ready to fetch your first real exercise.

# How to debug

When a test fails, a message is displayed describing what went wrong and for which input. You can also use the fact that ```console output``` will be shown too. You can write to the console using:

```go
import "fmt"
fmt.Println("Debug message")
```

Note: When debugging with the in-browser editor, using e.g. ```fmt.Print``` will not add a newline after the output which can provoke a bug in __go test --json__ and result in messed up test output.

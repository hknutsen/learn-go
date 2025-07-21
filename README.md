# Learn Go

## Build

1. Change to the `hello` directory:

   ```bash
   cd hello
   ```

1. Build the application:

   ```bash
   go build
   ```

1. Add the Go install directory to your path:

   ```bash
   export PATH="$PATH:$(go env GOPATH)/bin"
   ```

1. Install the application:

   ```bash
   go install
   ```

1. Run the application:

   ```bash
   hello
   ```

## References

- [Get started with Go](https://go.dev/doc/tutorial/getting-started)
- [Create a Go module](https://go.dev/doc/tutorial/create-module)
- [Call your code from another module](https://go.dev/doc/tutorial/call-module-code)
- [Return and handle an error](https://go.dev/doc/tutorial/handle-errors)
- [Return a random greeting](https://go.dev/doc/tutorial/random-greeting)
- [Return greetings for multiple people](https://go.dev/doc/tutorial/greetings-multiple-people)
- [Add a test](https://go.dev/doc/tutorial/add-a-test)
- [Compile and install the application](https://go.dev/doc/tutorial/compile-install)

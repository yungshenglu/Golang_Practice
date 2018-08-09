# Tutorial 1 - Start

In this tutorial, we will start a famous "Hello World" program to introduce some basic concept about *Go*.

> Notice: Before starting, please make sure that your machine has already installed *Go* packages.

---
## Operation

```bash
$ go
Go is a tool for managing Go source code.

Usage:

	go command [arguments]

The commands are:

	build       compile packages and dependencies
	clean       remove object files and cached files
	doc         show documentation for package or symbol
	env         print Go environment information
	bug         start a bug report
	fix         update packages to use new APIs
	fmt         gofmt (reformat) package sources
	generate    generate Go files by processing source
	get         download and install packages and dependencies
	install     compile and install packages and dependencies
	list        list packages
	run         compile and run Go program
	test        test packages
	tool        run specified go tool
	version     print Go version
	vet         report likely mistakes in packages

Use "go help [command]" for more information about a command.

Additional help topics:

	c           calling between Go and C
	buildmode   build modes
	cache       build and test caching
	filetype    file types
	gopath      GOPATH environment variable
	environment environment variables
	importpath  import path syntax
	packages    package lists
	testflag    testing flags
	testfunc    testing functions

Use "go help [topic]" for more information about that topic.
```

* **Go run** - used to run program with golang
    ```bash
    $ go run main.go
    Hello world!
    ```
* **Go build** - generate an execution file of your program
    ```bash
    $ go build main.go
    $ ./main
    Hello world!
    ```

---
## Practice

* Run `main.go` on your own machine
    ```bash
    $ go run main.go
    Hello world!
    ```

---
## Author

* [David Lu](https://github.com/yunshenglu)
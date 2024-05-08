### This is the Complete Tutorial and learning and getting ready for landing a Job as a GoLang Backend Developer


GO IS FAST, SIMPLE AND PRODUCTIVE
Generally speaking, compiled languages run much faster than interpreted languages, and Go is no exception.

Go is one of the fastest programming languages, beating JavaScript, Python, and Ruby handily in most benchmarks.

However, Go code doesn't run quite as fast as its compiled Rust and C counterparts. That said, it compiles much faster than they do, which makes the developer experience super productive. Unfortunately, there are no swordfights on Go teams...

### COMPARING GO'S SPEED
Go is generally faster and more lightweight than interpreted or VM-powered languages like:

* Python
* JavaScript
* PHP
* Ruby
* Java
<br>However, in terms of execution speed, Go does lag behind some other compiled languages like:

* C
* C++
* Rust
* Go 
<br>Is a bit slower mostly due to its automated memory management, also known as the "Go runtime". Slightly slower speed is the price we pay for memory safety and simple syntax!


<Img src = "https://storage.googleapis.com/qvault-webapp-dynamic-assets/course_assets/tUIWLob.png" ></Img> 

## THE COMPILATION PROCESS
Computers need machine code, they don't understand English or even Go. We need to convert our high-level (Go) code into machine language, which is really just a set of instructions that some specific hardware can understand. In your case, your CPU.

The Go compiler's job is to take Go code and produce machine code. On Windows, that would be a .exe file. On Mac or Linux, it would be any executable file. The code you write in your browser here on Boot.dev is being compiled for you on Boot.dev's servers, then the machine code is executed in your browser as Web Assembly.

### A NOTE ON THE STRUCTURE OF A GO PROGRAM
We'll go over this all later in more detail, but to sate your curiosity for now, here are a few tidbits about the code.

1. package ```main``` lets the Go compiler know that we want this code to compile and run as a standalone program, as opposed to being a library that's imported by other programs.
2. ```import fmt``` imports the ```fmt``` (formatting) package. The formatting package exists in Go's standard library and lets us do things like print text to the console.
3. ```func main()``` defines the ```main``` function. main is the name of the function that acts as the entry point for a Go program.
# go-wasm

### Links

[Quick Tutorial: Write Go, Run WASM! - DEV Community](https://dev.to/cia_rana/quick-tutorial-write-go-run-wasm-2ilf)

### Install and run

Go 1.11 is officially released, so all the notes about using go beta 1.11 can be ignored.

1. Ensure you have go 1.11 installed

`go version`

2.  Build the .wasm file according to the shell script

`./build.sh`

3.  Run the web server to serve the file

`go run server.go`

4.  Open the web page at http://localhost:8000/wasm_exec.html

5.  Right-click to inspect and navigate to the console tab.

6.  Click the "Run" button on the HTML page and witness printing to the console.

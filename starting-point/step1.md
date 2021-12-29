# Variable Declarations and Type Conversions

Let's start by looking at some simple variable declarations. In your editor, create a file called `variables.go` and copy the following code into it:

```go
package main

import "fmt"

func main() {
    var x int = 10 // full variable declaration format
    var y = 20     // type isn't needed, since the default type for the numeric literal 20 is int
    var z int      // type is specified, but value isn't, initializing z to the zero value for int (0)
    
    fmt.Println(x,y,z)
}
```{{copy}}

In your terminal, type `go run variables.go`{{execute}} 

Notice that it outputs `10 20 0` 

PUT IN STUFF FOR := using int, byte and float64, try assigning to each other, show that you can't compile
without the type conversion.




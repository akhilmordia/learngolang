# learngolang
packages and snippets created while learning golang

package structure:
```
package1(directory):
	package1.go
package2(directory):
	package2.go
```

installation: go.mod
```
module main

go 1.14

require (
	github.com/akhilmordia/learngolang v1.0.1
	github.com/akhilmordia/learngolang/v2 v2.0.1
)
```
example code:
```golang
package main

import (
	"fmt"

	"github.com/akhilmordia/learngolang/v2/alpha" //note how the path changes after v2
)

func main() {
	result := alpha.Divide(1, 1) //todo: division by zero
	fmt.Println("Divide(1/1) => ", result)

}
```

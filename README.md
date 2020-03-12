# learngolang
packages and snippets created while learning golang

package structure:
```
package1(directory):
	package1.go
package2(directory):
	package2.go
```

installation:
```
github.com/akhilmordia/learngolang v1.0.1 (<-the version that you want to use)
```
example code:
```golang
package main

import (
	"fmt"

	"github.com/akhilmordia/learngolang/alpha"
)

func main() {
	result := alpha.Divide(1, 1) //todo: division by zero
	fmt.Println("Divide(1/1) => ", result)

}
```

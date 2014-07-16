# Go Detective

## Usage

```go
package main

import "fmt"
import "github.com/kyleterry/go-detective"

func main() {
    detective.Init()
    d := detective.CollectData()
    fmt.Println(d)
}
```

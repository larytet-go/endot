# endot

What is the difference between these two notations
```
var a []int{}

a := []int{}
```

What does it print?
```
for i:=0;i < 10;i++ {
    go func() {
        v++
        fmt.Println("%d", i)
     }()
  }
```

What does it print?
```
v := 0
for i:=0;i < 10;i++ {
    go func() {
        v++
     }()
  }
  fmt.Println("%d", d)
```

What does it print?
```
  for v := range []str{"1", "2", "3"} {
    go func() {
        fmt.Println(v)
     }
  }
```

Write a boolean expression comparing `b1` and `b2`
```
type C struct {
    c int
}

type A struct {
    c C
}

type B struct {
    a A
    b int
    s *string
}
var b1 B
var b2 B
```

Is it a correct code?
```
type A intterface{}
type B=A
func a(b B) {
}
```

What happens in this loop?
```
a := []int{}
for i := 0;i < 1_000_000;i++ {
    a = append(a, i)
}
```


How can I have an anonymous interface? For exampe, can I get rid of the `I` in the following code?
```
type I interface{}
```

What is C in `ACID`?

loose coupling/tight coupling in architecture ?

how `index` is implemeted in a database?

What is `escape analysis` in Go?

Is the function runs O(1)
```
func emptyFunction(v ...interface{}) {
}
```

What is `interface{}` (an empty interface) used for?

Complexity of search in a binary tree?

Search in a sorted array is always faster than search in a binary tree: true or false?


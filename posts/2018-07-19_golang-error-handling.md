Today I learned

- go error returns and the beauty of it
``` go
if err != nil {
    return fmt.Errorf("method not found: %s", err)
}
```

this will passed up the chain and you could later read it for example like:

method not found: method not implemented: errorXYZ

this builds up another kind of stack trace (not a technical stack trace)

___



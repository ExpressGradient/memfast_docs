# EXISTS
Check if a key exists in the data store.

### Syntax:
```
EXISTS <key>
```

### Examples:
```
Command: EXISTS hello
Returns: false
```

```
Command: SET hello world
Command: EXISTS hello
Returns: true
```
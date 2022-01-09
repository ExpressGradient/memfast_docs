# SET
To set a Key-Value pair in the data store use the SET command.

### Syntax:
```
SET <key> <value>
```

### Example:
This would set `world` to `hello`:
```
Command: SET hello world
Returns: Inserted!
```

To update `hello` to `universe`, use the SET command again:
```
Command: SET hello universe
Returns: world
```
This command returns the previous value of `hello`.
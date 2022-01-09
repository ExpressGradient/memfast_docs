# SETSYNC
Set a Key-Value pair and sync it to other nodes in the network.

### Syntax:
```
SETSYNC <network-name> <key> <value>
```

### Example:
Connect to `ws://localhost:3030` and set `hello` to `world`.
```
Command: SETSYNC dummy_net hello world
Returns: Synced!
```

Now connect to `ws://localhost:3031` and check if `hello` is `world`.
```
Command: GET hello
Returns: world
```

You can even change the value of `hello` from `3031` node and sync it to other nodes.
```
Command: SETSYNC dummy_net hello universe
Returns: Synced!
```
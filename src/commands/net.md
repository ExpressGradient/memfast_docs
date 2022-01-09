# NET
Creates a network of MemFast nodes that needs to be synchrnoized.

### Syntax:
```
NET <name> <num-of-nodes> [...<node-ip>]
```

### Example:
```
Command: NET dummy_net 2 http://localhost:3030 http://localhost:3031
Returns: Created!
```
This command creates `dummy_net` network with 2 nodes. To be used with `SETSYNC` command.

> Note: Make sure that the nodes are running before running this command.
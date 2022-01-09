# DUMP
Dumps all the Key-Value pairs into a CSV file on demand.

### Syntax
```
DUMP <path-to-file>
```

### Example:
```
Command: SET name Sheldon
Command: SET friend Leonard
Command: SET wife Amy

Command: DUMP dump.csv
Returns: Dumped!
```
The table below shows the Key-Value pairs in the `dump.csv` file.  
<table>
    <tr>
        <th>Key</th>
        <th>Value</th>
    </tr>
    <tr>
        <td>name</td>
        <td>Sheldon</td>
    </tr>
    <tr>
        <td>friend</td>
        <td>Leonard</td>
    </tr>
    <tr>
        <td>wife</td>
        <td>Amy</td>
</table>

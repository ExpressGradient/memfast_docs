# Getting Started
There are two ways to install MemFast:
* [Windows Executable](https://github.com/ExpressGradient/memfast/releases/tag/v0.2.0-alpha.1)
* [Build from Source](https://github.com/ExpressGradient/memfast)

Specify the Port as a first argument while running the executable or build from source.

## Connect to MemFast
There are two ways to connect to a MemFast instance:
* WebSocket Endpoint
* POST Endpoint

## Making Queries
* From WebSocket Endpoint: Send the query as a simple text message.
```
SET key value
```
* From POST Endpoint: Send the query as a JSON object.
```json
{
  "query": "SET key value",
}
```
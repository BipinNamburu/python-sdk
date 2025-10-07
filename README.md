# MCP Python SDK
The MCP protocol defines three core primitives that servers can implement:
| Primitive | Control               | Description                                         | Example Use                  |
|-----------|-----------------------|-----------------------------------------------------|------------------------------|
| Prompts   | User-controlled       | Interactive templates invoked by user choice        | Slash commands, menu options |
| Resources | Application-controlled| Contextual data managed by the client application   | File contents, API responses |
| Tools     | Model-controlled      | Functions exposed to the LLM to take actions        | API calls, data updates      |
### Server Capabilities
MCP servers declare capabilities during initialization:
| Capability   | Feature Flag                 | Description                        |
|--------------|------------------------------|------------------------------------|
| `prompts`    | `listChanged`                | Prompt template management         |
| `resources`  | `subscribe`/`listChanged`| Resource exposure and updates      |
| `tools`      | `listChanged`                | Tool discovery and execution       |
| `logging`    | -                            | Server logging configuration       |
| `completions`| -                            | Argument completion suggestions    |
## Documentation
- [API Reference](https://modelcontextprotocol.github.io/python-sdk/api/)
- [Model Context Protocol documentation](https://modelcontextprotocol.io)
- [Model Context Protocol specification](https://spec.modelcontextprotocol.io)
- [Officially supported servers](https://github.com/modelcontextprotocol/servers)
## Contributing
We are passionate about supporting contributors of all levels of experience and would love to see you get involved in the project. See the [contributing guide](CONTRIBUTING.md) to get started.
## License
This project is licensed under the MIT License - see the LICENSE file for details.

---
Contributed by Comet Assistant

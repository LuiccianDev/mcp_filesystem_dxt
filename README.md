
<div align="center">
  <h1> MCP Server Local Filesystem</h1>
  <p>
  <em>Server for manipulating files and documents via MCP</em>
  </p>

  [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
  [![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-brightgreen)](https://modelcontextprotocol.io)
  [![Node.js](https://img.shields.io/badge/Node.js-%3E=20.0.0-green)](https://nodejs.org/)
    [![MCPB](https://img.shields.io/badge/MCPB-%40anthropic--ai%2Fmcpb-blue)](https://github.com/anthropics/mcpb)

</div>

## Description

This project contains the configuration and files required for the local MCP (Model Context Protocol) server.

## Project Structure

- `manifest.json`: Main configuration file.

## Requirements

- Node.js
- Install the MCPB extension with the following command:

```bash
npm install -g @anthropic-ai/mcpb
```

For more information about MCPB, visit [MCPB on GitHub](https://github.com/anthropics/mcpb).

## Installation

## Usage

1. Clone this repository to your local machine.
2. Configure the `manifest.json` file as needed.
3. Obtain and add your Notion credentials in the configuration.
4. Package the extension by running:

    ```bash
    mcpb pack
    ```

    This will generate the `.mcpb` file.

5. Install the `.mcpb` file in Claude Desktop from Settings > Extensions > Advanced Settings > Extension Installation. You will then be prompted to enter your Notion credentials.
6. Start MCP Server and verify the integration with Notion.

For more details about credentials and configuration, see the original project [Notion MCP Server](https://github.com/makenotion/notion-mcp-server).

## Resources Used

Some resources and configuration for this project were used from [Model Context Protocol Servers](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem).

## License

This project includes software under the MIT license from Anthropic, PBC. See the [LICENSE](LICENSE) file for more details.

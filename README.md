# Job Searchoor MCP Server

An MCP server implementation that provides job search functionality.

## Tools

get_jobs

Get available jobs with filtering options
Inputs:

sinceWhen (string): Since when to get available jobs. e.g., '1d' or '1w' (only days and weeks are supported)
keywords (string[], optional): Keywords to filter jobs by
excludeKeywords (string[], optional): Keywords to exclude from the jobs
isRemote (boolean, optional): Whether to filter jobs by remote work

## Usage with Claude Desktop

Add this to your claude_desktop_config.json:

```json{
"mcpServers": {
    "job-search": {
        "command": "npx",
        "args": ["-y", "job-searchoor"]
    }
}
```

License

This MCP server is licensed under the MIT License. This means you are free to use, modify, and distribute the software, subject to the terms and conditions of the MIT License. For more details, please see the LICENSE file in the project repository.

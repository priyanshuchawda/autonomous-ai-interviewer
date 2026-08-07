Connect to Claude Desktop
Drop this into ~/Library/Application Support/Claude/claude_desktop_config.json and restart Claude Desktop.

Your API key (shown once)
ck_live_xjblAocdzLkvepc4_L5GFxycT811HFesVLq63u8Zymc

We never show this again. Save it somewhere safe.

claude_desktop_config.json

Copy
{
  "mcpServers": {
    "breeth": {
      "command": "npx",
      "args": [
        "-y",
        "mcp-remote",
        "https://mcp.thebreeth.com/mcp",
        "--header",
        "Authorization: Bearer ck_live_xjblAocdzLkvepc4_L5GFxycT811HFesVLq63u8Zymc"
      ]
    }
  }
}

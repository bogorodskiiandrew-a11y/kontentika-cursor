# Kontentika for Cursor

Connect Cursor to your Kontentika workspace for content, publishing, inbox, analytics and advertising workflows. The tools available depend on the permissions and accounts you select when you connect.

## Connect

1. Install the plugin in Cursor and enable its Kontentika MCP server.
2. Use Cursor's OAuth sign-in prompt. In Kontentika, select your workspace and choose **Read only** to start.
3. Review the access and confirm. Ask Cursor to read your workspace with `workspace_context`.
4. Use the tools and schemas in Cursor's live catalog. For clients using the legacy catalog, advertising reads use `advertising_console`. Claude exposes them as `read_advertising_cabinet`.

For manual installation, copy the configuration in [mcp.json](mcp.json) into your Cursor MCP settings. Review or revoke access under **AI agents** in Kontentika.

The review workspace contains synthetic data and has no connection to live advertising accounts.

- [Connector guide](https://kontentika.app/connector-guide.md)
- [Connector privacy policy](https://kontentika.app/connector-privacy.html)
- [Support](mailto:info@kontentika.app)

The MIT license covers the files in this repository.

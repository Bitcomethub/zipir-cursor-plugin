# Zıpır for Cursor

A Cursor plugin that connects the hosted [Zıpır](https://zipirapp.com) MCP server (`https://api.zipirapp.com/mcp`, OAuth 2.1 + PKCE) and adds one skill for turning a document into a video lesson with a source citation on every scene.

- Tools: `list_formats`, `list_voices`, `list_lessons`, `create_lesson`, `get_lesson`, `edit_lesson`, `approve_lesson`, `rerender`, `get_download`, `get_usage`, `delete_lesson`
- Nothing renders until the user approves the storyboard.
- Sign-in happens in the browser when Cursor first connects; the plugin stores no credentials.
- API docs: https://zipirapp.com/en/api/ · Support: merhaba@zipirapp.com

License: MIT (this plugin package). The Zıpır service itself is a hosted product by VitrinAI Digital Studio.

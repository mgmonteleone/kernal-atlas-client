# kernal-atlas-client

The OAuth Client ID Metadata Document Kernal's LiteLLM router uses as its `client_id` when people sign in to the MongoDB Atlas remote MCP server (`https://mcp.mongodb.com`).

Served at https://mgmonteleone.github.io/kernal-atlas-client/client.json. It holds no secrets: a public client (`token_endpoint_auth_method: none`, PKCE) whose redirect URIs are corp-only Kanopy hosts.

Source of truth: `10gen/kernal-poc`.

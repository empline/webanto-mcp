# Webanto MCP setup for Cline

Use the hosted endpoint `https://webanto.com/api/mcp` with Streamable HTTP. Read
README.md for the IDE settings example and the native Cline CLI add command.
The CLI transport flag is `http`; the IDE type is `streamableHttp`.

Preserve the user's existing MCP entries and keep `autoApprove` empty. Install
no local backend, hooks or additional dependencies for this connection.

A Webanto account and OAuth consent are required. Use Cline’s OAuth connection flow. Select the intended business and review the requested scopes before allowing access. A privately configured API key is also supported by Webanto; never put a real credential in a public example.

After connecting, discover the actual tool schemas. Test one read-only tool;
do not use registration, reporting, AI generation, billing or publication as a
setup probe. Do not invent credentials or grant broader scopes to pass a test.
Never write an account token or secret into a public file, issue or transcript.
OAuth consent and native approval remain separate user actions. Tool discovery
alone is not an execution grant.

Official setup: https://webanto.com/ai/mcp
Support: support@webanto.com
Privacy: https://webanto.com/privacy
Terms: https://webanto.com/terms

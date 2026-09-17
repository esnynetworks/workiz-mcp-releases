# workiz-mcp-releases

Public version pointer for the private ESNY Workiz MCP connector. Installed
connectors read `latest.json` at startup to tell users when a newer version is
released. It contains only the latest version number and release link — no
code, no credentials. Updated by `npm run release:latest` in the private repo.

---
'@sveltejs/vite-devtools-svelte': minor
---

New `mcp` option: `svelteDevtools({ mcp: false })` turns off the MCP endpoint, so the dev server writes no registry entry or token and prints no MCP registration command. It defaults to `true`, so nothing changes unless you set it.

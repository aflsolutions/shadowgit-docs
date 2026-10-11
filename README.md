# ShadowGit documentation

Source of [docs.shadowgit.com](https://docs.shadowgit.com), built with [Mintlify](https://mintlify.com).

## Preview locally

Needs Node.js 20.17 or later.

```bash
npx mint dev            # preview at http://localhost:3000
npx mint broken-links   # check internal links
```

## Phrases

Every phrase the docs suggest asking is tested by the MCP server's eval, `scripts/eval-docs-phrases.ts` in [shadowgit-mcp](https://github.com/aflsolutions/shadowgit-mcp). When you add or change a phrase here, change it there too and run `npm run eval`.

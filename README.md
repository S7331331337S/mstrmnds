# mstrmnd Cursor plugin

Cursor plugin repository for mstrmnd.

## Included

- **mstrmnd**: rules, skills, agents, commands, hooks, MCP, and scripts

## Validation

Run:

```bash
node scripts/validate-template.mjs
```

## Submission checklist

- The plugin has a valid `.cursor-plugin/plugin.json`.
- The marketplace manifest points to the real plugin folder.
- All frontmatter metadata is present in rule, skill, agent, and command files.
- Logos are committed and referenced with relative paths.
- `node scripts/validate-template.mjs` passes.
- The repository link is ready for submission to the Cursor team (Slack or `kniparko@anysphere.com`).

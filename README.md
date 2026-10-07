# Commertize Agents — Agent Skill

An agent skill for **Commertize Agents**: it teaches an AI agent to read Commertize's
public marketplace of tokenized real-world assets — live offerings and their public
terms, SPV leverage disclosure, and published market commentary — through the public,
unauthenticated API at `https://api.commertize.com`.

The skill is read-only. It needs no key, no account and no registration, and nothing in
it can transact.

## Install

```bash
npx skills add Commertize-Inc/agent-skill
```

Works with agents that load `SKILL.md` skills, including Claude Code, Cursor and Codex.

## What's inside

```
commertize/
├── SKILL.md                     # the skill: endpoints, field meanings, rules for agents
└── references/
    ├── api-reference.md         # endpoint-by-endpoint reference
    ├── data-model.md            # enumerations, tokenomics fields, leverage derivation
    └── mcp-server.md            # the same surface as typed MCP tools
```

If your runtime speaks MCP, the same surface is available as typed tools from the
Commertize Agents MCP server: https://github.com/Commertize-Inc/mcp-server

## Disclaimer

Nothing in this repository, or returned by the API it describes, is an offer, a
solicitation, or a recommendation to buy or sell any security. It is not investment,
legal, or tax advice.

## License

Apache-2.0. See [LICENSE](LICENSE).

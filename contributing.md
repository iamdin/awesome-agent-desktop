# Contribution Guidelines

Thanks for taking the time to contribute. Please make sure your suggestion fits the scope of this list before opening a pull request.

## Scope

This list covers **AI agent products** — finished, user-facing things someone can install or sign up for.

In scope:

- Desktop apps that run, orchestrate, or review agents
- Agentic IDEs and editors
- Terminal and CLI agents
- Terminal multiplexers and session managers for agents
- Web, mobile, and remote clients
- Session monitors and companion tools

Out of scope:

- Frameworks, SDKs, and agent libraries
- MCP servers, prompt collections, and skill packs
- Model providers and inference endpoints
- Anything that is a building block rather than a product

When a product spans several form factors, file it under the one it leads with.

## Adding an entry

Open a pull request that adds a single line to the appropriate section:

```markdown
- [Name](URL) - Short description.
```

Requirements:

- One line per entry. Descriptions start with a capital letter and end with a period.
- Keep entries in case-insensitive alphabetical order within their section.
- For open-source projects, link the GitHub repo and use its own description.
- For everything else, link the official website and use its own description.
- Use plain ASCII unless the product name requires otherwise.
- Disambiguate same-named projects with a parenthetical owner, for example `openwork (different-ai)`.
- Verify the link resolves, and that a GitHub link is not a redirect from a renamed or transferred repo.

Add a new section only when at least three entries would live in it, and update the Contents list in the same pull request.

## Removing an entry

Pull requests that remove dead links, abandoned products, or entries that fall outside the scope above are welcome. Say briefly why in the description.

## Pull requests

- One product per pull request.
- Title the pull request `Add Name to the list` or `Update Name description`.
- Say in a sentence what the product does and why it belongs here.

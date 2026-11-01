# Learn to code with Claude

Resources for learning to code with Claude Code as a tutor, not as a ghostwriter: you write the code, Claude guides, explains and reviews.

This is the setup I use to learn Python while building real projects.

## What's inside

| File | What it is |
| --- | --- |
| [`CLAUDE.md`](CLAUDE.md) | Instructions that keep Claude Code in "tutor mode": one step at a time, hints before solutions, no edits to your files unless you ask. Adapts itself to you with a short setup the first time. |

## How to use the CLAUDE.md

1. Copy [`CLAUDE.md`](CLAUDE.md) into the root of your project.
2. Start Claude Code in the project folder. It reads `CLAUDE.md` automatically and, the first time, asks you a few questions (language, level, how much help you want, whether you use massCode).
3. Claude rewrites the file with your answers and removes the setup section.
4. Start a new session, so Claude works from the adapted version.

Prefer to do it by hand? Replace the `[bracketed]` parts, delete the optional sections you don't need, and remove the Setup section.

Tweak it as you go. If Claude does something that gets in the way of learning, add a rule. If a rule creates noise, remove it. The last line of the file ("don't end every message with a question") exists because an earlier version did exactly that, and it got in the way.

## Tools mentioned

- [massCode](https://github.com/massCodeIO/massCode) - free, open-source snippet manager with a built-in MCP server. Used by the optional "Snippets" section to save every snippet in three fragments: commented code, a prose description, and the same code without comments for practice.
- [Obsidian MCP Connector](https://github.com/istefox/obsidian-mcp-connector) - Obsidian plugin that gives Claude local access to your notes through MCP.

## Background

I write about this setup in my newsletter: [frankveglio.substack.com](https://frankveglio.substack.com).

## License

[CC0 1.0](LICENSE) - public domain. Copy it, change it, use it however you like, no attribution required.

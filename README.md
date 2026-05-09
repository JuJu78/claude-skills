# Claude Code skills — catalogue

A growing collection of [Claude Code](https://docs.claude.com/claude-code) skills I publish open-source. Each skill is a self-contained agent workflow that turns a recurring editorial, SEO or brand-audit task into a one-line invocation inside a Claude Code session.

Skills are auto-discovered from their `SKILL.md` and trigger when their description matches your prompt. See [Anthropic's documentation](https://docs.claude.com/claude-code/skills) for the full installation and troubleshooting guide.

---

## Catalogue

| Skill | What it does | Repo |
|---|---|---|
| **entity-territory-audit** | Audit the named-entity gap between a target URL and its top-ranked competitors. Surfaces the typed entities the page is missing, scored by priority. | [JuJu78/entity-territory-audit](https://github.com/JuJu78/entity-territory-audit) |
| **writers-room** | Multi-agent editorial workshop that turns a brief into a publication-ready web article. Real Task-tool sub-agent orchestration, programmatic verification, self-extending mode catalog, persistent feedback loop. Outputs both Markdown and a self-contained HTML preview. | [JuJu78/writers-room](https://github.com/JuJu78/writers-room) |

More skills land here as they are extracted from my private workflow and made generic enough to publish.

---

## Install one

```bash
git clone https://github.com/JuJu78/<skill-name>.git ~/.claude/skills/<skill-name>/
```

Start a Claude Code session — the skill is now available. Trigger phrases live in each skill's `SKILL.md` frontmatter.

---

## License

Every skill in this catalogue ships under the MIT license in its own repository. Forking, copying and adapting are encouraged.

---

## Author

Maintained by **Julien Gourdon** — [julien-gourdon.fr](https://julien-gourdon.fr).
Pull requests and issues welcome on each individual skill repository.

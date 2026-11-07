# Install Vision

Vision is a portable Agent Skill folder licensed under MIT. The license applies only to the files in this standalone Skill package; it does not cover the existing Dirro MCP or other files in the enclosing repository.

Use the method supported by your host. These steps are manual; the package does not install software, connect an MCP, or grant an AI extra project access. Read [EVALUATION_GUIDE.md](EVALUATION_GUIDE.md) for optional prompts and safe feedback suggestions.

## Codex

Unzip the release and copy the complete vision folder, including SKILL.md and LICENSE, into either:

- Project: .agents/skills/vision/
- User-wide: ~/.agents/skills/vision/

The project location makes Vision available to work in that repository; the user location makes it available across your projects. Keep the references/, examples/, agents/, and VERSION files beside SKILL.md. Open or refresh a Codex session so the host can discover the Skill. Codex features and discovery behavior depend on the installed client.

Official guidance: [OpenAI Codex CLI documentation](https://developers.openai.com/api/reference/cli) and the [Agent Skills specification](https://agentskills.io/specification).

## Claude Code

Unzip the release and copy the complete vision folder into either:

- Project: .claude/skills/vision/
- User-wide: ~/.claude/skills/vision/

Keep all package files together. Start or refresh a Claude Code session so it can discover the Skill. Claude Code may make Skills available through automatic selection or a slash command; use the behavior documented for your installed version.

Official guidance: [Claude Code Skills](https://code.claude.com/docs/en/skills) and the [Agent Skills specification](https://agentskills.io/specification).

## Claude environments with custom Skill uploads

Use the release ZIP when the Claude environment supports custom Skill uploads:

1. Confirm **Skills** and **code execution and file creation** are enabled for the account or workspace.
2. Open **Customize → Skills** and choose the upload or add-Skill option.
3. Upload the Vision release ZIP with the vision/ package folder at its root.
4. Follow the host's prompts to finish enabling it.

The menu and eligibility requirements can change. If the account does not expose custom Skill uploads, use Claude Code's folder installation above where applicable. Do not assume a web chat, Desktop app, or plan supports uploads without checking its current interface.

Official guidance: [Use Skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude).

## Version and verification

This package is Vision 1.0.0. To remove it, delete only the vision folder from the installation location you chose. Claude and Codex installation and design effectiveness were not tested by the implementation team; host compatibility remains to be verified by actual users.

# blueprint skill (Claude Code)

A Claude Code skill for building single-canvas and multi-sheet HTML blueprints with Prezi-style zoom, where every view is exactly 16:9.

## Install

Clone this repository straight into your Claude Code skills folder:

```bash
git clone https://github.com/peterhc72/blueprint.git ~/.claude/skills/blueprint
```

The same command works in Git Bash or PowerShell on Windows (`~` is `C:\Users\<your-name>`). Restart Claude Code after cloning. The skill is used automatically when you ask for a blueprint, for example "make a blueprint of ...".

Update:

```bash
git -C ~/.claude/skills/blueprint pull
```

Without git, use **Code → Download ZIP** on GitHub, unzip it, and rename the folder so that the skill file sits at `~/.claude/skills/blueprint/SKILL.md`.

## Contents

- `SKILL.md`: the skill rules
- `references/`: the reference build Claude reuses for structure and style (opens directly in a browser)
  - `SG-Innovation-Ecosystem-V1.0_EXT.html`: cover, multiple sheets and zoomed frames. Public edition: official logos and third-party photographs are not included.
  - `manifests/`: the manifest JSON for that build

For the original version of the reference build, please contact Peter CHANG.

Works well alongside the `frontend-slides` skill (https://github.com/zarazhangrui/frontend-slides).

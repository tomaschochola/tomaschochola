# tomaschochola

Public profile of Tomáš Chochola, Enterprise Architect focused on full-stack DevSecOps, cloud, and container platforms.

## Stack

- Language: Markdown on Node 24
- Runtime: GNU/Linux
- Libraries: none
- Package manager: npm

## Toolchain

- Format: prettier 3.x, trimmer
- Lint: none beyond format
- Test: none
- Audit: npm audit

## Devcontainer

- Base: official Node
- User: node
- Sidecars: none
- Up: `make up`
- Execute: `devcontainer exec --workspace-folder . <command>`
- Down: `make down`

## Makefile

- `update` — refresh locks, only tool that may touch them
- `fix` — auto-fix, may dirty tree
- `check` — full gate: doctor + lint + analyze + audit
- `doctor` — tree and toolchain ok
- `lint` — prettier + trimmer checks
- `analyze` — npm checks
- `audit` — dependency audit
- `postcreate` — first-time setup, runs automatically on create
- `stop` — stop container, keep it
- `down` — stop and remove container
- `clean` — drop generated files
- `distclean` — drop everything rebuildable
- `rebuild` — full rebuild, only when broken

## Layout

├── Makefile
├── .editorconfig
├── .devcontainer/
├── package.json
├── prettier.config.js
├── README.md
├── LICENSE
├── AUTHORS.md

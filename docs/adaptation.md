# Adaptation notes

Based on GitHub Primer’s official GitHub VS Code theme repository at fixed revision cd78e5e4e7bcf132a6f428ae0f32264bb1b729cf; the upstream repository provides both light and dark themes. The Tine role mapping is an independent adaptation.

## Sources

- repository: https://github.com/primer/github-vscode-theme/tree/cd78e5e4e7bcf132a6f428ae0f32264bb1b729cf
- license: https://github.com/primer/github-vscode-theme/blob/cd78e5e4e7bcf132a6f428ae0f32264bb1b729cf/LICENSE
- officialThemeAnnouncement: https://github.blog/changelog/new-github-themes-for-vs-code/

## Mapping decisions

- Light and dark main canvases were compared with the installed Codex GitHub defaults. The Primer repository provides the GitHub VS Code theme; links, accents and surface tiers are independent Tine role mappings and have not been verified as exact matches to every pinned upstream value.
- Tine stepped surfaces, selection, mark and semantic tag roles are mapped adaptations; the GitHub theme also includes roles that Tine’s 21-token API cannot represent.
- Specified text and background pairs were checked with the local synthetic browser fixture; that does not cover every host state.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.

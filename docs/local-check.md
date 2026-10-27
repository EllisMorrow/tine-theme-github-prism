# Local check summary

- Theme: GitHub · Prism 0.1.1
- Manifest SHA-256: `251e45ca188d4b62ce7fdab705fa118982a015579775575f091f5536ad63c73a`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 15.8:1, title 15.8:1, link 5.19:1, tag 5.05:1, code 13.95:1, mark 14.66:1, chosen 13.89:1.
  - Dark: body 16.02:1, title 16.02:1, link 6.11:1, tag 5.64:1, code 12.88:1, mark 11.28:1, chosen 9.72:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.

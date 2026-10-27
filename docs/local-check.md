# Local check summary

- Theme: Absolutely · Prism 0.1.1
- Manifest SHA-256: `9cd9ed2c3f1310b983b3a616216650a5793a55119a73591ca91208472d2aab74`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 13.09:1, title 13.09:1, link 5.33:1, tag 5.33:1, code 11.88:1, mark 11.66:1, chosen 11.55:1.
  - Dark: body 13.09:1, title 13.09:1, link 5.56:1, tag 5.56:1, code 11.15:1, mark 11.01:1, chosen 10.92:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.

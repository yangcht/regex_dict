# Some commonly used regex:

## Useful tools online:
- Testing live: [regexr](https://regexr.com)
- Visualizer & editor: [regex-vis](https://regex-vis.com)

## Finding things excluding the comment block:
- length no longer than 80 characters: `(?<!/\*(?:(?!\*/)[\s\S\r])*?)\b(.{80,})\b`


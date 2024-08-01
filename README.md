# Some commonly used regex:

## Finding things excluding the comment block:
- length no longer than 80 characters: `(?<!/\*(?:(?!\*/)[\s\S\r])*?)\b(.{80,})\b`


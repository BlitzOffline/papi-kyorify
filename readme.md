## kyorify
A simple "wrapper" placeholder that converts legacy-formatted placeholders to MiniMessage-formatted
ones (referred to as Kyorifying). I originally created this for [ChatChat](https://github.com/HelpChat/ChatChat).

It's incredibly simple:
- chop off `kyorify_` prefix and parse it with PAPI
- replace & with §
- swap out formatters for MM tags, closing other tags when needed

## Usage
Just put `kyorify` in front of any placeholder.
 For example, `%vault_prefix%` would become `%kyorify_vault_prefix%`.

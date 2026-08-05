# Ayu for Codex

An unofficial [Ayu](https://github.com/ayu-theme/ayu-colors) theme port for [OpenAI Codex](https://github.com/openai/codex).

## Variants

- `ayu-dark`
- `ayu-mirage`
- `ayu-light`

## Codex CLI

Copy the desired `.tmTheme` file to `~/.codex/themes/` and select it in `~/.codex/config.toml`:

```toml
[tui]
theme = "ayu-dark"
```

Restart Codex after changing the configuration.

## Codex Desktop

The matching `themes/*.import.txt` files contain theme-import payloads for Codex Desktop. They set the UI palette and IoskeleyMono Nerd Font Propo; the `.tmTheme` file provides syntax highlighting.

## Upstream

- Application: [OpenAI Codex](https://github.com/openai/codex)
- Theme: [Ayu](https://github.com/ayu-theme/ayu-colors)

## License

Apache-2.0. Ayu palette copyright 2016-present Ike Kurghinyan.

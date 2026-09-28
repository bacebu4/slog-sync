# slog sync

Obsidian plugin that syncs the `YYYY.MM.md` worklog files in a vault folder (`log/` by default, set in the plugin's settings) with a slog
server (optimistic lock + diff3 merge, live updates over SSE). Only useful with a slog
server. This repo holds built releases only.

Install with [BRAT](https://github.com/TfTHacker/obsidian42-brat): "Add beta plugin" →
`bacebu4/slog-sync`, enable it, then set the server URL in the plugin's settings.

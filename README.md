# Lilloweb

**A browser built for developers.** By 3Level Labs.

Lilloweb is a Chromium browser with a workspace per project, a developer toolkit
beside the page, and an agent that can work in your tabs.

## Download

Get the latest Windows (64-bit) installer from the
[**Releases**](../../releases) page of this repository.

Windows may show a SmartScreen warning the first time you run the installer,
because it is not code-signed yet. Choose **More info**, then **Run anyway**.

## Use it with your coding agent

Lilloweb includes a local MCP server, so agents such as Claude Code, Codex and
Cursor can read and work in your open tabs.

1. In Lilloweb, open **Connect**.
2. Choose **Copy setup**.
3. Paste it into your agent.

The connection stays on your computer and needs a token. Agent JavaScript is off
by default. The agent skill that teaches an agent how to use Lilloweb is
[gnobob/lilloweb-skill](https://github.com/gnobob/lilloweb-skill).

## Help and feedback

Found a bug or have an idea? Open an issue on this repository's
[Issues](../../issues) page. For security problems, please do not open a public
issue; read [SECURITY.md](SECURITY.md).

## License and credits

© 2026 3Level Labs. Lilloweb is proprietary software.

Lilloweb includes software derived from [Dive](https://github.com/ronaldxdale09/dive-browser)
(MIT License) and is built on Chromium and other open-source components, each
under its own license. See [NOTICE.md](NOTICE.md).

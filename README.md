# Claude Code Theme

> **No affiliation.** This is an independent, Claude Code-inspired theme. It is not affiliated with, endorsed by, or sponsored by Anthropic or Claude Code. "Claude" and "Claude Code" are trademarks of Anthropic.

A Claude Code-inspired look for Hermes Desktop, plus a context-window meter beside the model switcher.

## What it changes
- One flat surface colour for sidebar and chat; the chat backdrop image is hidden.
- Right-aligned, fit-to-text user bubbles; a single-border rounded composer.
- Side-panel file viewer as one floating rounded card (tab strip included).
- Softer selected sidebar rows; working-session arc matches the row corners.
- Rounded white (light) / charcoal (dark) dropdown menus.
- Light and dark palettes that follow your Appearance mode.

## Context meter
A ring next to the model switcher shows how full the current chat's context window is.
Click it for the exact token count and, when your provider reports them, your plan usage limits
(read from Hermes's own `session.usage`; the plugin makes no network calls of its own).

## Settings
Settings → Plugins → Claude Code Theme: optional custom accent colour for light and dark mode (off by default).

## Disclosure
- No network calls, no credentials, no shell commands, no background processes.
- Stores only its own accent preference via the plugin storage API.
- Styling targets Hermes Desktop markup with CSS; a Desktop update may change some details.

## Install
```bash
hermes plugins install aliilhami/hermes-claude-code-theme
```
Then enable it in Settings → Plugins.

## Licence
MIT

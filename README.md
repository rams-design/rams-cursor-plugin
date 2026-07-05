# Rams — Design Review for Cursor

Accessibility (WCAG 2.1) and visual design review for UI code, with concrete
fixes. Made by [rams.ai](https://www.rams.ai/?utm_source=skill&utm_medium=cursor-plugin).

## Install

From the Cursor Marketplace: open **Customize** in the sidebar, search for
**rams**, and install. Or browse [cursor.com/marketplace](https://cursor.com/marketplace).

(Plugin format per the [Cursor plugins docs](https://cursor.com/docs/plugins).)

## Use

Ask for a review naturally ("review this component for design issues") or run
the `rams` command on a file. The review covers accessibility (alt text,
labels, keyboard access, focus, contrast, touch targets) and visual design
(spacing, typography, color, component states), each finding with a fix.

## Canonical source

The review content is maintained at
[rams.ai/rams.md](https://rams.ai/rams.md) — that file is canonical. A nightly
workflow syncs this repo to it, so the plugin never drifts.

## The full engine

This plugin runs locally as a heuristic review. The hosted engine at
[rams.ai](https://www.rams.ai/?utm_source=skill&utm_medium=cursor-plugin)
reviews every pull request with 119 scored rules, verified re-reviews, and
one-click fix suggestions.

MIT licensed.

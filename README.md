# JSON Formatter — Feedback

[English](README.md) | [中文](README_zh.md)

This repo is for collecting feedback and suggestions for [JSON Formatter](https://json.site).

Thanks for using JSON Formatter!

If you run into any issues or have ideas, feel free to let me know.

## How to Submit

- Go to [GitHub Issues](https://github.com/bygo/json.site/issues) and create a [new Issue](https://github.com/bygo/json.site/issues/new)
- Briefly describe your problem or suggestion
- Attach screenshots or sample JSON if needed

I'll check and get back to you as soon as I can. Thanks!

## Changelog

### 2026-08-09

- **Graph expand / collapse all** — toolbar button expands or folds every structural node in one click
- **Clickable edges** — wider hit targets; click a link to select the child node and highlight the chain
- **Smarter fold** — collapsing a node keeps child expand state so re-opening restores the previous layout
- **Faster pinch / trackpad zoom** — wheel and pinch zoom sensitivity doubled for quicker navigation

### 2026-08-08

- **Local-data privacy tip** — History panel shows a dismissible banner
- **Clearer graph text (Windows)** — fixed blurry labels when zoomed

### 2026-08-05

- **Graph view** — explore JSON as an interactive graph (pan, zoom, fullscreen, fit view)
- **Scalar arrays & highlighting** — graph nodes color scalars by type; scalar arrays show inline with per-element colors

### 2026-08-01

- **Tree font size** — tree values follow the global font size setting
- **Toolbar layout** — action bar wraps more cleanly on narrow screens

### 2026-07-30

- **Tree double-click edit** — fixed double-click to edit keys/values in the tree
- **Export fixes** — clearer errors for invalid JSON; more reliable multi-format export

### 2026-07-29

- **Editor scroll CLS** — reduced layout shift while scrolling the editor
- **Cell edit** — fixed accidental double-enter when starting cell edit

### 2026-07-27

- **Multi-format import/export** — upload and export CSV, Excel, YAML, XML, JSONL, Markdown, SQL, and more

### 2026-07-24

- **Tree virtual scrolling** — large JSON trees stay smooth
- **Column drag** — reorder table columns by dragging headers
- **Tree edit** — double-click a tree node to edit it

### 2026-07-21

- **Toggle columns** — hide table columns; edit them via the button in the top-left corner cell
- **Box-select delete** — select cells by box-drag and delete them

### 2026-07-08

- **JSON Path syntax update** — updated to standard JSON path syntax
- **Major table refactor** — virtual scrolling, Cartesian product select/copy, reworked UX

### 2026-06-28

- **One-click screenshot** — capture the formatted JSON as an image in a single click
- **Multi-language** — switch the interface language

### 2026-06-07

- **JSON path** — place the cursor on a node to extract its path (e.g. `[2].article.name`) straight into the filter
- **Keyboard shortcuts panel** — view and customize shortcuts, with browser default keys handled cleanly
- Fixed a scroll glitch when unfolding

<!-- changelog-synced: 1c19750fce1a23e221d1280f2497af2e1592a343 -->

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

### 2026-10-31

- **Open JSON from a link** — load and format URL-encoded JSON via `#json=`; existing compressed share links remain supported
- **Large integers in share links** — fixed precision loss when generating share links and when loading them in the lightweight editor
- **AI guide** — added a [guide for AI agents](https://json.site/docs/ai) with JavaScript and Python examples for generating viewer links, plus a documentation index at `/llms.txt`
- **Sharing FAQ** — added sharing instructions, an example link, and data privacy reminders to multilingual FAQs; feedback links now point to GitHub Issues

### 2026-10-24

- **Page not found** — invalid URLs now show a dedicated 404 page with a link back to JSON Formatter

### 2026-10-21

- **Home navigation** — added a JSON.site logo and link in the header to return to your language's homepage

### 2026-10-17

- **Caching improvements** — improved caching of editor resources for repeat visits while keeping update files fresh

### 2026-10-16

- **Privacy indicator** — added a dismissible browser-local processing reminder in the toolbar; hiding it is remembered
- **AI repair wording** — clearer labels and privacy notice explain that AI repair uploads data for processing

### 2026-09-16

- **JSONC** — settings toggle to allow JSON comments and trailing commas; formatting keeps comments

### 2026-09-15

- **Share JSON** — toolbar button builds a compressed share link in the URL hash; opening it restores the data

### 2026-08-12

- **Link open fix** — clicking http(s) links with query params in the editor no longer mangles `=` and `&`

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

<!-- changelog-synced: 2a5ad3863077111cdb6f84deadb0c5a5140daa37 -->

## Star History

<a href="https://www.star-history.com/?repos=bygo%2Fjson.site&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=bygo/json.site&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=bygo/json.site&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=bygo/json.site&type=date&legend=top-left" />
 </picture>
</a>

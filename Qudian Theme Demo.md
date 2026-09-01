# Qudian Theme Demo

A living reference for the Qudian theme's palette and how it maps onto Obsidian's UI. Swatches below pull live from the theme's CSS variables, so if the palette changes, this page updates with it.

## Raw palette

<div style="display:flex; flex-wrap:wrap; gap:4px;">
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-bg);"></div>bg</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-surface);"></div>surface</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-fg);"></div>fg</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-white);"></div>white</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-green);"></div>green</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-green-dim);"></div>green-dim</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-red);"></div>red</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-orange);"></div>orange</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-yellow);"></div>yellow</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-yellow-dim);"></div>yellow-dim</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-gold);"></div>gold</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-blue);"></div>blue</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-blue-dim);"></div>blue-dim</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-blue-soft);"></div>blue-soft</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-cyan);"></div>cyan</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-cyan-dim);"></div>cyan-dim</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-magenta);"></div>magenta</div>
<div style="width:110px; text-align:center; font-family:monospace; font-size:0.75em;"><div style="height:56px; border-radius:4px; border:1px solid var(--qd-surface); background:var(--qd-magenta-soft);"></div>magenta-soft</div>
</div>

## Headings

# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading

## Text formatting

Normal text sits on `--text-normal`. **Bold text** uses `--bold-color`. *Italic text* uses `--italic-color`. ***Bold italic*** combines both. ==Highlighted text== uses `--text-highlight-bg`. ~~Strikethrough~~ for comparison.

> A blockquote, styled with `--blockquote-color` and `--blockquote-border-color`.

## Links

- Resolved internal link: [[HomePage]]
- Unresolved internal link: [[Nonexistent Demo Page]]
- External link: [Obsidian](https://obsidian.md)

## Tags

#demo #theme-test #qudian


## Checkboxes

- [x] Completed task
- [ ] Open task

## Table

| Element | Variable | Notes |
|---|---|---|
| Header row | `--table-header-background` | Uses surface color |
| Alt row | `--table-row-alt-background` | |
| Border | `--table-border-color` | |

## Code

Inline code: `const qud = "viridian";`

```js
// Comment — --code-comment
const greeting = "Hello, Qud"; // string — --code-string
const count = 42; // number — --code-value

class Wanderer {
  function speak() { // keyword — --code-keyword
    return `${greeting} (${count})`; // function — --code-function
  }
}
```

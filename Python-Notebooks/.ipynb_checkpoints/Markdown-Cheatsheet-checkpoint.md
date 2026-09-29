# Markdown Cheatsheet

A quick reference for writing in Markdown cells in your Jupyter notebooks. This covers what you'll actually use for taking process notes — not the full Markdown spec.

## Headers

```markdown
# Header 1 (big section title)
## Header 2 (subsection — this is what we use for Imports, Failure Log, etc.)
### Header 3 (smaller still)
```

## Text formatting

```markdown
**bold text**
*italic text*
`inline code`
```

- `**bold text**` → **bold text**
- `*italic text*` → *italic text*
- `` `inline code` `` → `inline code` (use this for variable/function names in your notes)

## Lists

Bullet list:
```markdown
- first point
- second point
```

Numbered list:
```markdown
1. first step
2. second step
```

## Blockquotes

```markdown
> A blockquote — useful for pasting in an error message or a line from the textbook you're responding to.
```

## Dividers

```markdown
---
```
Three dashes on their own line makes a horizontal divider — good for separating steps.

## Links

```markdown
[link text](https://example.com)
```

## Code blocks (for showing, not running, code)

Use a fenced code block when you want to paste in and discuss a snippet in a Markdown cell — this is different from an actual working code cell, which runs the code.

<pre>
```python
some_code_here()
```
</pre>

---

## Things that trip people up

- **Leave a blank line** above and below any list, header, or code block — Markdown often won't render correctly without it.
- **`#` means something different depending on the cell type.** In a Markdown cell, `#` makes a header. In a code cell, `#` starts a comment. Same character, opposite jobs.
- **You still have to run a Markdown cell** (Shift+Enter) to see it rendered — it won't format itself just by clicking away.

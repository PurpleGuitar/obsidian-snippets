# obsidian-snippets
CSS snippets for use with Obsidian

Files prefixed with `z-` change things globally and are meant to be turned on
only when needed (e.g. for printing).

## Optional classes

Add these to a note's `cssclasses` property.  Naming follows two patterns:

- `no-<area>-<thing>` turns something off (e.g. `no-bases-header`)
- `<area>-<modifier>` turns something on (e.g. `ul-striped`)

| Class | File | Effect |
| --- | --- | --- |
| `no-bases-header` | bases.css | Hide the Bases toolbar |
| `no-bases-thead` | bases.css | Hide Bases table column headings |
| `no-bases-group-property` | bases.css | Hide the group-by property name |
| `callout-borders` | callouts.css | Show a border on every callout |
| `no-checkbox-strikeout` | checkboxes.css | Don't strike out completed tasks |
| `no-code-copy-button` | code.css | Hide the copy button on code blocks |
| `no-dataview-inline-fields` | plugin-dataview.css | Hide Dataview inline fields |
| `no-embed-decorations` | embeds.css | Make embeds blend into the page |
| `no-embed-indent` | embeds.css | Remove embed padding, border, and background |
| `no-embed-titles` | embeds.css | Hide embed titles |
| `no-embed-headings` | embeds.css | Hide h1–h4 inside embeds |
| `embed-show-as-h1`, `-h2`, `-h3` | embeds.css | Style embed titles as headings |
| `no-h-underline` | headers-h1-h2-h3-underline.css | No underline on h1–h3 |
| `no-h1-underline`, `no-h2-underline`, `no-h3-underline` | headers-h1-h2-h3-underline.css | No underline on one heading level |
| `h1-clear-float`, `h2-clear-float`, `h3-clear-float` | headers-h1-h2-h3-underline.css | Start headings below floated content |
| `no-h-spacing` | headings.css | Remove extra space above headings that follow body text |
| `no-h-margin-top` | page.css | Remove all space above headings |
| `no-external-link-icon` | links.css | Hide the external link arrow |
| `no-link-underline` | links.css | Don't underline internal links |
| `ul-striped`, `ul-striped-dark` | lists.css | Stripe list items |
| `no-ul-bullets` | lists.css | Hide bullets and indentation guides |
| `ul-narrow` | lists.css | Reduce list indentation |
| `ul-flatten` | lists.css | Remove all list indentation and bullets |
| `no-ul-margin-top` | lists.css | Remove the space above lists |
| `ul-float-images` | lists.css | Float images in list items (experimental) |
| `no-mermaid-resize` | mermaid.css | Show Mermaid diagrams at natural size |
| `no-inline-title` | page.css | Hide the inline title |
| `no-p-block-margin` | page.css | Remove paragraph spacing |
| `no-text-wrap` | page.css | Don't wrap text |
| `responsive-columns` | page.css | Flow the page into columns by screen width |
| `print-h1-page-break` | print.css | Start each h1 on a new printed page |
| `print-two-columns`, `-three-`, `-four-` | print.css | Print in columns |
| `no-table-center` | tables.css | Don't center tables |
| `no-table-hover` | tables.css | Don't highlight rows on hover |
| `table-invisible` | tables.css | Hide table borders and shading |
| `table-small-text` | tables.css | Smaller table text (experimental) |

## Callout options

Add after the callout type, e.g. `> [!info|sidebar|no-title]`.

| Option | Effect |
| --- | --- |
| `sidebar` | Float the callout to the right at 40% width |
| `no-icon` | Hide the icon |
| `no-title` | Hide the title (and icon) |
| `no-background` | Remove background, margin, and padding |
| `border` | Show a border |
| `cleft`, `cright` | Offset left or right, for conversations |
| `portrait-right`, `portrait-right-10` … `-50` | Float an image right with no title or background |

## Image spans (image-placement.css)

Wrap an embed in a span, e.g. `<span class="portrait-right">![[img.png]]</span>`.

`portrait-right` (30%), `portrait-right-20`, `-25`, `-30`, `-35`, `-50`,
`portrait-right-200px`, `icon-right`, `icon-left`

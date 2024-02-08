# Personal **[UltiSnips][ultisnips-url]** Snippet Library

This repository contains snippets in the **[UltiSnips][ultisnips-url]** format
for personal use. They have been gradually developed over time based on my own
usage patterns and preferences.

This library includes snippets for the following file types:

- **TypeScript** (*typescript*) -- **\*.ts** files
- **TypeScript React** (*typescriptreact*) -- **\*.tsx** files
- **Markdown** (*markdown*) -- **\*.md** files

## Snippets

All snippets are listed below; the first word in **bold** is the snippet
shortcut, and the **code block** following it illustrates the expanded content.

### Markdown

The following snippets are active for the **markdown** filetype.

#### General

- **rlk** -- `[id]: content 'title'`
- **bq** -- `> text`
- **url** -- `<url>`
- **email** -- `<email>`

#### Images

- **img** -- `![alt](url)`
- **imgv** -- `![alt][url-var]`
- **imglk** -- `[![alt](image-url)](link-url)`
- **imgvlkv** -- `[![alt][image-var]][link-var]`

#### Links

- **lk** -- `[label](url tooltip)`
- **lkv** -- `[label][url-var]`
- **lkc** -- `` [`label`](url tooltip) ``
- **lkcv** -- `` [`label`][url-var] ``
- **lki** -- `*[label](url tooltip)*`
- **lkiv** -- `*[label][url-var]*`
- **lkic** -- `` *[`label`](url tooltip)* ``
- **lkicv** -- `` *[`label`][url-var]* ``
- **lkb** -- `**[label](url tooltip)**`
- **lkbv** -- `**[label][url-var]**`
- **lkbc** -- `` **[`label`](url tooltip)** ``
- **lkbcv** -- `` **[`label`][url-var]** ``
- **lkbi** -- `_**[label](url tooltip)**_`
- **lkbiv** -- `_**[label][url-var]**_`
- **lkbic** -- `` _**[`label`](url tooltip)**_ ``
- **lkbicv** -- `` _**[`label`][url-var]**_ ``

#### Code

- **co** -- `` `text` ``
- **it** -- `*text*`
- **itc** -- `` *`text`* ``
- **bo** -- `**text**`
- **boc** -- `` **`text`** ``
- **boi** -- `***text***`
- **boic** -- `` ***`text`*** ``

#### Headings  

- **h1** -- `# header`
- **h2** -- `## header`
- **h3** -- `### header`
- **h4** -- `#### header`
- **h5** -- `##### header`
- **h6** -- `###### header`

#### Code Blocks

- **cob** -- `` ```language...``` ``
- **cobjs** -- `` ```js...``` ``
- **cobbash** -- `` ```bash...``` ``
- **cobjson** -- `` ```json...``` ``

[ultisnips-url]: https://github.com/SirVer/ultisnips 'Ultisnips'

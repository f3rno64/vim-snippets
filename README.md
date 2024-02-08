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

### TypeScript

The following snippets are active for the **typescript** filetype.

#### Exports

- **exp** -- `export`
- **exdef** -- `export default`
- **exob** -- `export { ... }`

#### Imports

- **im** -- `import`
- **imreact** -- `import react`
- **imclassnames** -- `import classnames`
- **imU** -- `import * as U from 'utils'`

#### Lodash Imports

- **im_in** -- `import _includes`
- **im_fil** -- `import _filter`
- **im_sub** -- `import _subtract`
- **im_mp** -- `import _map`
- **im_k** -- `import _keys`
- **im_v** -- `import _values`
- **im_fl** -- `import _flatten`
- **im_fld** -- `import _flattenDeep`
- **im_un** -- `import _uniq`
- **im_isud** -- `import _isUndefined`
- **im_isni** -- `import _isNil`
- **im_isnl** -- `import _isNull`
- **im_iseq** -- `import _isEqual`
- **im_ise** -- `import _isEmpty`
- **im_iso** -- `import _isObject`
- **im_iss** -- `import _isString`
- **im_iser** -- `import _isError`
- **im_isd** -- `import _isDate`
- **im_isb** -- `import _isBoolean`
- **im_isn** -- `import _isNumber`
- **im_isa** -- `import _isArray`
- **im_isfi** -- `import _isFinite`
- **im_isfu** -- `import _isFunction`
- **im_unb** -- `import _uniqBy`
- **im_co** -- `import _compact`
- **im_s** -- `import _sum`
- **im_mi** -- `import _min`
- **im_ma** -- `import _max`
- **im_ch** -- `import _chunk`

#### Lodash Functions

- **_in** -- `_includes`
- **_fi** -- `_filter`
- **_sub** -- `_subtract`
- **_mp** -- `_map`
- **_k** -- `_keys`
- **_v** -- `_values`
- **_fl** -- `_flatten`
- **_fld** -- `_flattenDeep`
- **_un** -- `_uniq`
- **_isud** -- `_isUndefined`

#### Lodash Function Assignment

- **_isni** -- `const ... = _isNil(...)`
- **_isnl** -- `const ... = _isNull(...)`
- **_iseq** -- `const ... = _isEqual(...)`
- **_ise** -- `const ... = _isEmpty(...)`
- **_iso** -- `const ... = _isObject(...)`
- **_iss** -- `const ... = _isString(...)`
- **_iser** -- `const ... = _isError(...)`
- **_isd** -- `const ... = _isDate(...)`
- **_isb** -- `const ... = _isBoolean(...)`
- **_isn** -- `const ... = _isNumber(...)`
- **_isa** -- `const ... = _isArray(...)`
- **_isfi** -- `const ... = _isFinite(...)`
- **_isfu** -- `const ... = _isFunction(...)`
- **_unb** -- `const ... = _uniqBy(...)`
- **_co** -- `const ... = _compact(...)`
- **_s** -- `const ... = _sum(...)`
- **_mi** -- `const ... = _min(...)`
- **_ma** -- `const ... = _max(...)`
- **_ch** -- `const ... = _chunk(...)`

#### TypeScript General

- **clo** -- `console.log`
- **cle** -- `console.error`
- **ret** -- `return`
- **gfu** -- `generator function`
- **afu** -- `anonymous function`

#### Control Flow

- **if** -- `if statement`
- **el** -- `else`
- **elif** -- `else if`
- **for** -- `for loop`

#### Destructuring

- **c{** -- `const { ... } = ...`
- **c[** -- `const [ ... ] = ...`
- **l{** -- `let { ... } = ...`
- **l[** -- `let [ ... ] = ...`

#### Test Functions

- **desc** -- `describe`
- **it** -- `it`
- **ita** -- `it async`
- **expe** -- `expect`
- **expetext** -- `expect(...).toHaveTextContent(...)`
- **expeeq** -- `expect(...).toEqual(...)`
- **expedef** -- `expect(...).toBeDefined()`
- **expesnap** -- `expect(...).toMatchSnapshot()`

[ultisnips-url]: https://github.com/SirVer/ultisnips 'Ultisnips'

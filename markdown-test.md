# Markdown Syntax Tests
---
## Headers

# This is an `<h1>` tag
## This is an `<h2>` tag
### This is an `<h3>` tag
#### This is an `<h4>` tag
##### This is an `<h5>` tag
###### This is an `<h6>` tag

### This heading has 1 id {#my_id}
### This heading has 2 classes {.heading1 .heading2}

---

## Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

---

[Link](link.url "Title")

## Codeblocks
```js {highlight=2-4}
const code = 'code'
// I am code
console.log('blah')
// tada
const moreLines = false
```

```javascript {.codeblock-class}
function add(x, y) {
  return x + y
}
```

```javascript {.line-numbers}
function add(x, y) {
  return x + y;
}
```

---

*[abbr]: abbreviation
This is an abbr!

==mark==

Definition
: definition

> Blockquote
>
> more quote!

- [ ] task
- [x] completed task

List
- list
- list!
- I am list

Ordered List!
1. list
2. list
3. list

Table | table
--- | ---
cell | cell

<kbd>ctrl</kbd>

Footnote [^1]
[^1]: I am a footnote!

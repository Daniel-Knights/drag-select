# drag-select ⚡️

> _Make any element selectable with just a few lines of code_ 👊

-   Lightweight ☁️
-   Easy to use 🌞
-   Compatible with any frontend framework 🔥

## Installation

```bash
npm i drag-select
```

or...

```bash
yarn add drag-select
```

## Usage

```js
import { dragSelect, onSelected } from 'drag-select'

dragSelect('drag-box-class', 'selected-element-class') // Arguments are optional

onSelected(selected => {
    console.log(selected) // [div.selected-element-class, ...]
})
```

---

**Contributions welcome!**



<div align="center">
  <h3>Tailwind Atoms</h3>
</div>
<div align="center">
  Tailwind CSS plugin to get atomic components ready to use
</div>
<div align="center">
 with HTML & React: <code>button</code>, <code>input</code>, <code>checkbox</code> switch...
</div>

<br />

<div align="center">
  <a href="https://tailwindatoms.com/">Website</a> 
<span> · </span>
  <a href="https://tailwindatoms.com/">Documentation</a> 
<span> · </span>
  <a href="https://twitter.com/christoribeiro">Twitter</a>
</div>

## Setup

Install the plugin:

```zsh
yarn add tailwindatoms --dev
yarn add @tailwindatoms/react # if you use React
```
or 
```zsh
npm install tailwindatoms --save-dev
npm install @tailwindatoms/react # if you use React
```

Add the plugin to your Tailwind config:

```javascript
// tailwind.config.js
module.exports = {
  // ...
  plugins: [require("tailwindatoms")],
}
```


## Getting started

With **HTML**

```html
<button class="btn btn-primary">Submit</button>

<input type="text" class="input" />
<input type="checkbox" class="switch">
```

With **React**

```javascript
import { Button, Input } from "@tailwindatoms/react"

const MyPage = () => (
  <>
    <Button color="primary">Submit</Button>

    <Input type="text" />
    <Input type="switch" />
  </>
)

export default MyPage
```

## Documentation

Checkout the full documentation on [the official website][website].

[website]: https://tailwindatoms.com

# Tailwind Atoms

⚛️ Set of Tailwind CSS plugins to get atoms components ready to use with HTML & React. No need to design again a `button`, an `input` or a `checkbox` switch.


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

Add the plugin:

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

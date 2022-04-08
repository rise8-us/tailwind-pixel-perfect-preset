# tailwind-pixel-perfect-preset
A Tailwind CSS preset that replaces rem with px.

## Install
```shell
npm install --save-dev @rise8/tailwind-pixel-perfect-preset
# or
yarn add --dev @rise8/tailwind-pixel-perfect-preset
```

Update your `tailwind.config.js` to use the preset:

```js
//cjs
module.exports = {
  presets: [
    require('@rise8/tailwind-pixel-perfect-preset')
  ],
  // ...
}
```
```js 
//esm
import tailwindPixelPerfectPreset from '@rise8/tailwind-pixel-perfect-preset'

export default {
  presets: [
    tailwindPixelPerfectPreset
  ],
  // ...
}
```

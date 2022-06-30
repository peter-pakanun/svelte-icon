# Svelte Icon
I want to keep it simple and play nice with [Tailwind CSS](https://tailwindcss.com/).
You can use this with [Material Design Icons](https://materialdesignicons.com/) via the [@mdi/js](https://www.npmjs.com/package/@mdi/js) package.

## Usage
```
npm i -D @mdi/js https://github.com/peter-pakanun/svelte-icon
```

```svelte
<script>
  import Icon from 'svelte-icon';
  import { mdiAccount } from '@mdi/js';
</script>

<Icon d={mdiAccount} class="w-4 h-4" />
```

## Props

```
d:string      = SVG path data. (required)
class:string  = SVG class attribute. (optional)
fill:string   = SVG fill color. (optional) (default: "currentColor")
stroke:string = SVG stroke color. (optional) (default: "")
title:string  = content in title tag. (optional)
```
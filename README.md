# Svelte Icon
I want to keep it simple and play nice with [Tailwind CSS](https://tailwindcss.com/).
You can use this with [Material Design Icons](https://materialdesignicons.com/) via the [@mdi/js](https://www.npmjs.com/package/@mdi/js) package.

## Usage
```
npm i -D @mdi/js @peter-pakanun/svelte-icon
```

```svelte
<script>
  import Icon from '@peter-pakanun/svelte-icon';
  import { mdiAccount } from '@mdi/js';
</script>

<Icon d={mdiAccount} class="w-4 h-4 text-red-500" />
```

## Props

| Prop   | PropTypes | Default        | Details                                           |
|--------|-----------|----------------|---------------------------------------------------|
| d      | string    | required       | SVG path data.                                    |
| class  | string    | `null`         | SVG class attribute. e.g., `w-4 h-4 text-red-500` |
| fill   | string    | `currentColor` | SVG fill color.                                   |
| stroke | string    | `null`         | SVG stroke color.                                 |
| title  | string    | `null`         | content in title tag.                             |

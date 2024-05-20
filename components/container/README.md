# Container

Traditional container element to center content on the page modernized with a min() function.

## Usage

```html
<div class="container">
  Content...
</div>
```

## Settings

Set global custom properties `--container-max-width` and `--container-padding` to change the container's max-width and padding.

| Variable | Value |
| --- | --- |
| `--container-max-width` | `<length>\|<percentage>` |
| `--container-padding` | `<length>\|<percentage>` |

### Example
```css
:root {
  --container-max-width: 1200px;
  --container-gutter: 2rem;
}
```
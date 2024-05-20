# Dynamic Grid

Cutstomizable grid system that automatically wraps depending on a set minimum width of columns and the total number of columns at most.

## Usage

```html
<div class="dynamic-grid">
  <div>Item</div>
  <div>Item</div>
  <div>Item</div>
  <div>Item</div>
  <div>Item</div>
</div>
```

## Settings

Set custom properties `--grid-gap`, `--grid-columns` and `--grid-min-width` to change the grid's layout.

| Variable | Value |
| --- | --- |
| `--grid-gap` | `<length>\|<percentage>` |
| `--grid-columns` | `number` |
| `--grid-min-width` | `<length>\|<percentage>` |

### Example

```html
<div
  class="dynamic-grid"
  style="--grid-gap: 8px; --grid-columns: 4; --grid-min-width: 250px"
>
  <!-- Grid items... -->
</div>
```
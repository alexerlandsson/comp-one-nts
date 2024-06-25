# H Stack

Used to layout components horizontally similar to `HStack` from `SwiftUI`.

## Usage

```html
<div class="hstack">
  <div>Item</div>
  <div>Item</div>
</div>
```

## Settings

Set custom property `--hstack-gap` to change the spacing between items.

| Variable | Value |
| --- | --- |
| `--hstack-gap` | `<length>\|<percentage>` |

### Example

```html
<div class="hstack" style="--hstack-gap: 16px;">
  <!-- Items... -->
</div>
```
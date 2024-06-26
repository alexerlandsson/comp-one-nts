# V Stack

Used to layout components vertically similar to `VStack` from `SwiftUI`.

## Usage

```html
<div class="vstack">
  <div>Item</div>
  <div>Item</div>
</div>
```

## Settings

Set custom property `--vstack-gap` to change the spacing between items.

| Variable | Value |
| --- | --- |
| `--vstack-gap` | `<length>\|<percentage>` |

### Example

```html
<div class="vstack" style="--vstack-gap: 16px;">
  <!-- Items... -->
</div>
```
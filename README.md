# Toggle Switch (Using CSS only)

Simple example showing how to style a plain checkbox into a more UX-friendly toggle switch using only HTML and CSS.

## Structure

The input stays accessible, while a sibling span renders the switch.

```html
<label class="switch">
	<input class="switch_input" type="checkbox" role="switch">
	<span class="switch_track" aria-hidden="true"></span>
</label>
```

## Notes

- The checkbox element is not set to `display: none` to allow keyboard focus.
- `:focus-visible` provides a clear keyboard focus outline.
- `prefers-reduced-motion` disables transitions for people who prefer it.

# Step 5: Layout with Flexbox

This is what your page should look like after adding card containers and Flexbox layout.

## What changed in index.html

- The `<section>` content was replaced with three `<div class="card">` containers
- Each card has an `<h3>` heading and a `<p>` description

## What was added to style.css

- `nav` — `display: flex` and `gap: 20px` make the nav links sit side by side
- `section` — `display: flex` arranges the cards in a row, `justify-content: center` centres them, `gap` adds spacing, `flex-wrap: wrap` lets cards wrap to a new line if needed
- `.card` — white background, padding, rounded corners, fixed width, and a subtle shadow

## Key concepts

- **Flexbox** is activated with `display: flex` on a container
- `justify-content` controls horizontal alignment (centre, space-between, etc.)
- `align-items` controls vertical alignment
- `gap` adds space between flex items (much cleaner than using margins)
- `flex-wrap: wrap` lets items move to the next line when there is not enough room
- `box-shadow` adds depth — the format is: `horizontal-offset vertical-offset blur-radius colour`

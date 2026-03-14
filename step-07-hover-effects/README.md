# Step 6: Hover Effects and Transitions

This is what your page should look like after adding interactive hover effects.

## What was added to style.css

- `transition` on buttons and cards — makes changes animate smoothly
- `button:hover` — changes colour, lifts up slightly, adds a shadow
- `.card:hover` — lifts up and deepens the shadow
- `a:hover` — changes link colour
- `nav a:hover` — changes nav link colour

## Key concepts

- `:hover` is a **pseudo-class** — it activates when someone moves their mouse over an element
- `transition` makes the change smooth instead of instant — `0.3s` means 0.3 seconds
- `transform: translateY(-5px)` moves the element up by 5 pixels
- You can transition multiple properties: `transition: transform 0.3s ease, box-shadow 0.3s ease`
- `ease` is a timing function that starts slow, speeds up, then slows down again

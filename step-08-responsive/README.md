# Step 7: Responsive Design

This is what your page should look like after adding responsive styles for mobile devices.

## What changed in index.html

- Added `<meta name="viewport" content="width=device-width, initial-scale=1.0">` inside `<head>`
- This tells mobile browsers to use the real screen width instead of pretending to be a desktop

## What was added to style.css

- A `@media` query at the bottom that activates when the screen is 600px wide or less
- Inside the media query: cards stack vertically, nav links stack vertically, heading shrinks

## Key concepts

- **Media queries** let you apply different styles at different screen sizes
- `@media (max-width: 600px)` means "if the screen is 600 pixels wide or less, use these rules"
- `flex-direction: column` changes Flexbox from a row layout to a stacked column layout
- The viewport meta tag is essential — without it, mobile browsers zoom out to show the desktop version

## How to test

- In your browser, drag the window to make it narrow
- Or open Developer Tools (F12 or right-click > Inspect), then click the mobile device toggle icon

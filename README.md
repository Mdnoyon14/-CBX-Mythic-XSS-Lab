# CBX's Mythic XSS Lab

## Setup

1. Clone or copy this folder to Termux:
   `cp -r my-server ~/my-server`

2. Run with Python:
   `cd ~/my-server && python3 -m http.server 8080`

3. Visit:
   `http://localhost:8080`

## Structure

- index.html → Main lab interface
- style.css → Glitchy neon styling
- logic.js → Payload engine
- assets/ → Optional logo or badge

## Challenge Flow

- Step 1: Basic `<script>` alert
- Step 2: Image error handler
- Step 3: SVG loader
- Step 4: iframe JS URI
- Step 5: body onload
- Step 6: input autofocus

More steps can be added with mutation, encoding, and filter bypass.

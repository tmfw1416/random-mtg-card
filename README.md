# Random Magic Card

A tiny static website that displays one random Magic: The Gathering card at a time.

## Hosting

This project is designed for GitHub Pages. Put `index.html` in a GitHub repository and enable Pages using the `main` branch and `/ (root)` folder.

## Important note about Gatherer

The original idea was to retrieve the random card from:
https://gatherer.wizards.com/random-card

Gatherer currently blocks automated/programmatic requests in ways that make a simple browser-only GitHub Pages implementation unreliable. This version therefore uses Scryfall's public card API and displays only the card image. The interface remains intentionally minimal.

Scryfall asks API users to keep requests reasonable; this app only makes one request each time the button is clicked.

## Files

- `index.html` — the entire website

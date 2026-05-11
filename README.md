# silly games

A collection of small, shareable browser games for two people.

## Games

### 🎭 Blind Reply
> `blind-reply/index.html`

Both players answer the same questions independently — no peeking — then see each other's answers revealed side by side.

**How it works:**
1. Player 1 writes the questions and answers them first
2. A link is generated — share it over WhatsApp, iMessage, etc.
3. Player 2 opens the link and answers the same questions (without seeing P1's answers)
4. When done, a final reveal link is generated showing both answers side by side

**Tech:** Pure HTML/CSS/JS — no backend, no database. All state is encoded in the URL hash using base64. Works as a static site on GitHub Pages.

## Setup (GitHub Pages)

1. Push to your repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your site will be at `https://<username>.github.io/<repo>/`

## Adding more games

Add a new folder with an `index.html`, then add a card for it in the root `index.html`.

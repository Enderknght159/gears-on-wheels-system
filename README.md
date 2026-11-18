# Gears on Wheels — protected documents

Static site with two AES-256-GCM encrypted documents (WebCrypto, PBKDF2-SHA256).

- `system.html` — the interactive system presentation
- `pricing.html` — the invoice / price offer
- `index.html` — links to both (each asks for a password)

Each gate page contains only the encrypted payload. The password is not stored in this repository.

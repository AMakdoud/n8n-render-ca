# n8n-render (easy mode, CA/FR)

### [![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/AMakdoud/n8n-render-ca)
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/AMakdoud/n8n-render-ca)


### How to install n8n on render.com for free

Follow these steps:

1. Click the button above.
2. Choose a blueprint name (e.g., "n8n").
3. Click "Create New Resources".
4. Apply.
5. In the Render dashboard → your `n8n` service → **Environment**.
6. Copy your public URL (purple link in header).
7. Paste that URL into the `WEBHOOK_URL` env var.
8. Wait ~1 minute for the instance to update.
9. Enjoy!

**Notes (CA/Québec):**
- Render n'a pas de région Canada; on utilise `oregon` (latence correcte pour le Québec).
- Locale par défaut: `fr`, fuseau: `America/Toronto`.

This instance is free for 90d, then database costs $7/mo on Render.

# n8n + PDF Merge (Railway starter)

This tiny starter lets you deploy **n8n** to [Railway](https://railway.app) **with the `n8n-nodes-pdf` community package already baked in**.  
Result: you can immediately use the **“PDF Merge”** node inside your workflows.

## Files

| File / map          | Wat het doet                                    |
|---------------------|-------------------------------------------------|
| `Dockerfile`        | Bouwt een eigen Docker‑image en installeert de PDF‑node |
| `package.json`      | Klein Node project—Railway cache werkt beter met dit bestand |
| `.env.example`      | Voorbeeld variabelen (kopiëren naar Railway → Variables) |

## Snelle start

1. **Fork of clone** dit project  
2. **Push** naar GitHub  
3. In Railway: **New Project → Deploy from GitHub Repo**  
4. Na de eerste build: ga naar tab **Variables** en voeg de key‑value‑paren uit `.env.example` toe  
5. Klik **Redeploy**  
6. Open je n8n‑URL; login; voeg een node toe en zoek op **PDF Merge**  

Klaar! ✨

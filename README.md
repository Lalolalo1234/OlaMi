# OlaMi — Observatorio Latinoamericano de la Minería (OLM)

Static web portal for the OLM (Observatorio Latinoamericano de la Minería), an OLAMI initiative. The site presents the regional scale-up of the CeProMin "demand-led mining" model, adapted from the institutional architecture of the Observatorio de Ingeniería de España, rendered as a single self-contained HTML page.

## Stack

- HTML (`index.html`) — inline CSS and JavaScript, no build step or external dependencies.

## Run Locally

Open `index.html` directly in a browser, or serve it with any static file server, e.g.:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Project Structure

- `index.html`: Full site — structure, styles, and tab-navigation script.

## Relationship to CeProMin

OLM is the proposed regional evolution of [CeProMin](https://github.com/Lalolalo1234/CeProMin) (Argentina). This repository is intentionally kept separate from CeProMin's for now — the two sites are not merged or cross-linked.

## License

This project is licensed under the MIT License. See `LICENSE`.

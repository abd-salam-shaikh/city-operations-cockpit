# CITY/OPS — Urban Operations Cockpit

An English-language smart-city dashboard demonstrating mobility, energy,
environmental and infrastructure operations with a responsive control-room UI.

## Live demo

[Open the CITY/OPS cockpit on GitHub Pages](https://abd-salam-shaikh.github.io/city-operations-cockpit/)

## Data modes

- `VITE_DATA_MODE=static` uses deterministic sample data and makes no API calls.
- `VITE_DATA_MODE=live` enriches weather and air-quality readings with the
  public Open-Meteo APIs. All other operational datasets remain illustrative.

GitHub Pages is deliberately configured for static mode.

## Local development

```bash
npm install
npm run dev:live
```

For the fully static version, use `npm run dev`.

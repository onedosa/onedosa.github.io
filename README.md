# PS4 Host

A browser-based PS4 exploit host with firmware detection, firmware-specific routing, GoldHEN payload delivery, and offline Application Cache support.

## Supported firmware ranges

- 5.05 / 5.07
- 7.00 – 8.52
- 9.00 – 9.60
- 10.00 – 11.02
- 11.50 – 12.02
- 12.50 – 13.00
- 13.02 – 13.52

## Structure

```text
/
├── index.html          # public entry / firmware detection
├── style.css           # shared UI
├── core/               # exploit chains, cache pages and payloads
├── README.md
└── SOURCE-NOTICE.md
```

The `core/` directory is intentionally kept self-contained so its relative paths and offline cache manifests remain stable.

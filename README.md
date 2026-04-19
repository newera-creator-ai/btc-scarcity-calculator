# Bitcoin Scarcity Visualizer

A single-page project that visualizes Bitcoin rarity based on your BTC holdings, including supply-based scarcity, population-based rarity, and land-area analogies.

## Demo
- Static single HTML page (`index.html`)
- Korean/English language toggle

## Key Features
- BTC input with quick-select buttons (0.01 / 0.1 / 0.5 / 1 / 5 / 10)
- Scarcity calculation against:
  - Total supply (21M BTC) — theoretical maximum
  - Effective supply (~16.51M BTC) — after deducting estimated lost coins (~3.5M)
- Satoshi-unit breakdown displayed on each scarcity card
- Population rarity shown as `1 in X people` based on estimated wallet distribution (Glassnode, BitInfoCharts)
- `10,000`-dot world population visualization
- Compact numeric fallback for ultra-rare ranges (sub-1 in the dot model)
- BTC → Earth land area analogy with nearest city comparison
- Korean/English toggle with `localStorage` persistence

## Data & Assumptions
- Uses address-distribution-based estimates (referencing Glassnode and BitInfoCharts)
- Addresses are not equal to unique individuals
- Snapshot-based logic (not real-time market data)
- For reference/entertainment only, not investment advice

## Project Structure
```text
.
├─ index.html
└─ README.md
```

## Run Locally
Open `index.html` directly in your browser.

## Deploy on GitHub Pages
1. Ensure `index.html` is in the repository root.
2. Go to your repository: `Settings` → `Pages`.
3. Select `Deploy from a branch`.
4. Choose Branch: `main` (or your branch), Folder: `/ (root)`.
5. Save and open the generated Pages URL.

## License
MIT

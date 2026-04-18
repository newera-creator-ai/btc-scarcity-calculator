# Bitcoin Scarcity Visualizer

A single-page project that visualizes Bitcoin rarity based on your BTC holdings, including supply-based scarcity, population-based rarity, and land-area analogies.

## Demo
- Static single HTML page (`index.html`)
- Korean/English language toggle

## Key Features
- BTC input with quick-select buttons
- Scarcity calculation against:
  - Total supply (21M BTC)
  - Effective supply (estimated)
- Population rarity shown as `1 in X people`
- `10,000`-scale world visualization
- Compact fallback view for ultra-rare ranges (sub-1 in the dot model)
- BTC-to-Earth-land-area analogy card
- Language preference persisted via `localStorage`

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

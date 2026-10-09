# Vietnam Trip Split

Phone-friendly expense splitter for Stirling and Ryan's Vietnam trip.

- Live app: https://claude.ai/artifact/Lw1KisxcAcci1NRFzs3rs3
- Source: `index.html` (published as a claude.ai Artifact with shared `db` storage)

## How it works
- Log each purchase: amount in đồng (`350k`, `1.2m` work), who paid, and the split
  (50/50, all for the other person, or just the payer's).
- The top card shows who owes whom, in ₫ and your home currency.
- When someone sends money, tap **Record payment** to zero the balance.
- Tap any entry to edit or delete it. Names and exchange rate live under **Settings**.

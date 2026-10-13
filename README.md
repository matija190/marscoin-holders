# MATO✦MΛRS Wallet & Marscoin Holders

Static website for **[matomarswallet.com](https://matomarswallet.com/)**.

- `index.html` – MATO✦MΛRS Wallet homepage
- `richlist/` – **Marscoin Holders**: circulating supply, distribution and every address holding at least 100 MARS, with the date and time (UTC) of its last transaction
  - `richlist/holders/`, `richlist/distribution/`, `richlist/api/` – sub-pages
  - `richlist/data.json`, `richlist/holders.json` – snapshot data computed from a Marscoin full node (UTXO set)

The data is a snapshot at a single block and is refreshed manually. Not financial advice.

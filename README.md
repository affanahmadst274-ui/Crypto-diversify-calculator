# Crypto Diversify Calculator — v2 (2025)

A simple, single-file web app to plan and visualize a **diversified crypto portfolio** by **sector → coin**.

Built entirely in **HTML, CSS, and JavaScript** — no backend required, just open it or host on **GitHub Pages**.

---

## 🚀 Features

- 🧮 **Edit sector allocations** and normalize to 100%.
- 💰 **Enter total investment** (any currency: USD / EUR / PKR / USDT).
- 🪙 **Custom coin weights** inside each sector (optional).
- ➕ **Add / Delete sectors and coins** dynamically.
- 💾 **Auto-save** to localStorage (keeps your data between sessions).
- 📊 **Instant calculation** of per-sector and per-coin investment amounts.
- 🌙 **Modern dark theme**, responsive layout, and minimal UI.
- ⚙️ **No dependencies**, works fully offline.

---

## 📂 Files

- **`crypto-diversify-calculator-v2.html`** → main app (ready to open or host)
- *(Optional)* Rename to `index.html` to make it the homepage of your GitHub Pages site.

---

## 🌐 How to Host on GitHub Pages

1. Create a new **public repository** on GitHub (e.g. `crypto-diversify-calculator`).
2. Upload the file:
   - Click **Add file → Upload files**.
   - Choose `crypto-diversify-calculator-v2.html` (or rename to `index.html` first).
   - Click **Commit changes**.
3. Go to **Settings → Pages**.
4. Under “Build and deployment,” choose:
   - **Source:** Deploy from branch  
   - **Branch:** `main`  
   - **Folder:** `/ (root)`
5. Click **Save** — wait a few moments for GitHub to deploy your site.
6. Visit the generated URL, usually:

https://affanahmadst274-ui.github.io/Crypto-diversify-calculator/



---

## 🧠 How to Use

1. **Open the webpage** (locally or via your GitHub Pages link).
2. The app automatically loads **2025 crypto sector defaults**:
- Store of Value, L1s, L2s, AI, RWA, DePIN, DeFi 2.0, Gaming/Metaverse, Meme/Community, Stablecoins.
3. **Edit sectors & allocations**
- Click inside “Allocation %” to change numbers.
- Total allocation shows at the top — use “Normalize to 100%” if needed.
4. **Edit coins**
- Click the “Edit coins” button or expand a sector to adjust coin weights.
5. **Enter your total investment** (any number) and pick a currency (USD / EUR / PKR / USDT).
6. Click **Calculate** to view:
- Sector allocation summary (% + amount)
- Per-coin breakdown (% + amount)
7. **Your changes auto-save** in the browser.
- Use **Reset to defaults** anytime to restore the template.

---

## ⚙️ Troubleshooting

| Problem | Solution |
|----------|-----------|
| No sectors showing | Click **Reset to defaults** to reload defaults. |
| Percentages don’t add up | Use **Normalize to 100%**. |
| Custom weights not working | Make sure the weights in that sector **sum to 100%**. |
| Data not syncing across devices | Saved locally via `localStorage`; not cloud-synced. |

---

## 🧩 Technical Notes

- **No frameworks**: 100% vanilla JavaScript, CSS, HTML.
- **Data persistence**: Browser `localStorage`.
- **Default dataset**: Defined in `defaultSectorsV2` (edit easily in code).
- Works offline — you can open the `.html` file directly in a browser.

---

## 🔮 Future Improvements (optional)

- CSV or PDF export
- Pie / Bar charts (visual portfolio breakdown)
- Shareable URL configuration
- Cloud save & import/export
- Live crypto prices (CoinGecko API integration)

Let me know if you want any of these added!

---

## ⚠️ Disclaimer

> This project is for **educational and portfolio-planning purposes only**.  
> It does **not provide financial advice** or guarantee performance.  
> Always perform your own research before making any investment decisions.

---

## 🪪 License

MIT License © 2025  
Free to use, modify, and share.

---

### 👨‍💻 Author
Created with ❤️ by **Ahmad** using ChatGPT-5.  
You can deploy it instantly on GitHub Pages or remix it for your own crypto tools.

---


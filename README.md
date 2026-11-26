# Global Supply Chain & Indian Mutual Fund Explorer

An interactive D3.js network & financial intelligence web application combining:

1. **🇮🇳 Nifty 50 Supply Chain** — Force-directed web covering all 50 index constituents and their listed Indian, unlisted/private, and global vendors, JVs, logistics partners, and key buyers.
2. **🇺🇸 Nasdaq-100 Supply Chain** — Supply chains across Nasdaq-100 tech, semiconductor, cloud/AI, healthcare, and consumer giants.
3. **🌐 Combined Cross-Market View** — Unified view highlighting shared Indian & global supply-chain hubs bridging both indices.
   - **📊 Company Financial History (3–5Y + YTD):** Clicking any listed company opens a right-side D3 grouped bar chart of Revenue and Net Profit for the last 3–5 fiscal years plus latest available YTD period (`314` covered listed companies via Screener.in, StockAnalysis, and Yahoo Finance).
4. **📈 Top-15 Bank & quant Mutual Fund Explorer (`#mf`)** — Three interactive D3 visualizations tracking **91 Direct Plan - Growth equity schemes** across India's Top 15 bank-associated AMCs plus **quant Mutual Fund** (with live AMFI NAVs & computed 1Y/3Y/5Y CAGRs, annualized volatility, and 3Y max drawdown):
   - **🕸️ Bank → AMC Constellation:** Concentric D3 orbital map linking Top 15 Indian banks (private, PSU, JV/historical, and distributor-only) to their associated AMCs and performance-scaled scheme nodes.
   - **🌌 Risk-Return Galaxy:** Quadrant bubble plot & Pareto efficiency frontier plotting 3Y annualized volatility vs 1Y/3Y/5Y CAGR.
   - **🏎️ ₹10,000 Wealth Race:** Interactive multi-fund normalized lump-sum trajectory comparator with monthly scrubbing crosshair and showdown presets.

**Live Site:** https://haydenpereira17.github.io/supply-chain-explorer/

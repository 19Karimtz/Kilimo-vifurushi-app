# 🌾 Kilimo-Vifurushi
### Smart Agricultural Finance Platform — Vijana Uchumi Challenge 2026

---

## 📱 How to Install as APK (Android)

### Option 1 — Chrome on Android (Recommended)
1. Open `index.html` on any web server (or use a local server)
2. Open Chrome browser on your Android phone
3. Navigate to the app URL
4. Tap the **⋮ menu** → "Add to Home Screen"
5. Tap "Install" — the app installs like a native APK ✅

### Option 2 — Using a Local Server
```bash
# With Python
python3 -m http.server 8080

# With Node.js
npx serve .
```
Then visit `http://localhost:8080` on your phone (same WiFi).

### Option 3 — Convert to true APK with Bubblewrap
```bash
npm install -g @bubblewrap/cli
bubblewrap init --manifest=https://your-url/manifest.json
bubblewrap build
```

---

## 🏗 App Architecture

### Three Dashboards (Triunity Model)

| Role | Color | Key Features |
|------|-------|--------------|
| 👨‍🌾 Farmer | Green | Credit Wallet, Farm Health, AI Recs, Market Prices |
| 💼 Investor | Blue | Bond Marketplace, Portfolio Map, Proof of Growth, Impact |
| 🏪 Agro-Dealer | Purple | QR Scanner, PIN Pad, Inventory, Settlement Ledger |

### Key Flows
- **Farmer Redemption**: Select voucher → Generate PIN/QR → Show to Dealer
- **Investor Funding**: Browse bonds → Select amount → Choose payment → Get certificate
- **Dealer Verification**: Scan/enter PIN → System verifies funds → Confirm delivery → Get paid

---

## 🎯 Vijana Uchumi Challenge Features
- ✅ AI crop recommendations
- ✅ Satellite farm monitoring  
- ✅ Agri-Bond marketplace with fractional funding
- ✅ Real-time market prices
- ✅ QR + PIN voucher redemption
- ✅ Instant dealer settlement
- ✅ Impact metrics dashboard
- ✅ Offline capability (Service Worker)
- ✅ USSD-ready UX (high contrast, simple flows)

---

*Kilimo-Vifurushi | Confidential Blueprint | Vijana Uchumi Challenge 2026*


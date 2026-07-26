# The $1B Decision — 1TCC × BCG

An interactive CFO simulation game built for the BCG exhibition booth.

🎮 **[Play the game](https://yanapetrovadev.github.io/tcc-game/)**

---

## About

You are CFO of a major manufacturer. Make 5 supply chain decisions under time pressure. Every choice moves your balance sheet — live.

Built by **1TCC** in partnership with **BCG**.

---

## How to Play

1. Choose **Demo mode** for an instant game with a fictional company
2. Or choose **My company** to enter your own financials for a personalised impact analysis
3. Answer 5 CFO decisions (60 seconds each)
4. See your FCF impact and Market Cap Upside on the results screen
5. Click **Get Full Report** to request a full CII analysis from the 1TCC team

---

## Features

- 📊 Live FCF bar chart updating after each decision
- 🏢 Personalised analysis using your company's real inventory & CCC data
- ✅ Green/red screen flash feedback on answers
- 📩 Microsoft Forms lead capture for follow-up
- 🔒 GDPR-compliant opt-in consent

---

## Technical Notes

### Dependencies (CDN — requires internet)
| Dependency | Purpose |
|---|---|
| [Barlow fonts](https://fonts.google.com/specimen/Barlow) | Typography |
| [Chart.js 4.4.1](https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js) | Live FCF bar chart |
| Google Apps Script webhook | Lead capture to Google Sheets |

### Deploying to GitHub Pages
1. Fork or upload this repository
2. Go to **Settings → Pages**
3. Set source to **main branch / root folder**
4. Your game will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

### Internal Lead Dashboard
Type `leads` on the attract screen to access the internal lead capture dashboard (visible only on the device running the game).

---

## Files

| File | Description |
|---|---|
| `index.html` | The complete game (single file) |
| `README.md` | This file |

---

*Built with 1TCC Corporate colours: Navy `#0d1b2e` · Yellow `#f5a623` · White*

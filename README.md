# 🩺 Health Dashboard

> Personal blood report trend tracker with Firebase persistence and Google Auth.

**Live:** https://prashant300.github.io/health-dashboard/

---

## Features

| Feature | Details |
|---|---|
| 🔐 Auth | Google Sign-in — private to one authorised email |
| 📊 Trend Charts | Sparkline chart per metric across all reports |
| 🚦 Status Indicators | Green / Yellow / Red per reference range |
| 💡 Insights Engine | Auto-detects improvements, regressions, new flags |
| ➕ Add Reports | Form to enter new blood test values any time |
| 🗑️ Delete Reports | Remove incorrect entries |
| ☁️ Firebase Firestore | All data persisted in cloud — never lost |
| 📱 Responsive | Works on mobile and desktop |

---

## Metric Groups Tracked

- **Metabolic** — Fasting Glucose, HbA1c
- **Lipids** — Total Cholesterol, LDL, HDL, Triglycerides, VLDL, Non-HDL, Ratios
- **Liver** — SGOT, SGPT, ALP, GGT, Bilirubin, Albumin, Protein, A/G Ratio
- **Kidney** — Uric Acid, Creatinine, BUN, Urea, Sodium, Potassium, Chloride
- **CBC** — Hemoglobin, RBC, WBC, Platelets, Differential, ESR, PDW
- **Iron** — Serum Iron, TIBC, UIBC, Transferrin Saturation
- **Vitamins** — Vitamin D, Vitamin B12, Calcium
- **Thyroid** — TSH, T3, T4
- **Hormones** — Testosterone, Prolactin, FSH, LH, Cortisol, PSA

---

## Tech Stack

- **Frontend:** Vanilla HTML/CSS/JS (single file, zero build step)
- **Auth:** Firebase Authentication (Google provider)
- **Database:** Firebase Firestore
- **Hosting:** GitHub Pages
- **Charts:** HTML5 Canvas (custom sparklines)
- **Fonts:** Fraunces + DM Mono (Google Fonts)

---

## Setup (for reference)

```
1. Firebase project → enable Firestore + Google Auth
2. Add authorized domain in Firebase Auth settings
3. Replace firebaseConfig in index.html
4. Deploy index.html to any static host
```

---

## How to Add a New Report

1. Open the dashboard → click **+ Add Report**
2. Enter the date and lab name
3. Fill in available values (leave others blank)
4. Click **Save Report**
5. Trends update automatically

---

## Report History

See [CHANGELOG.md](./CHANGELOG.md) for full update history.

# Changelog

All report additions and dashboard updates are logged here.

---

## [Dashboard v1.0.0] — 2026-05-30

### 🚀 Initial Release

**Dashboard features:**
- Google Auth (single-user private access)
- Firebase Firestore persistence
- Sparkline trend charts per metric (HTML5 Canvas)
- Smart insights engine (auto-detects improvements/regressions)
- Group filter tabs (Metabolic, Lipids, Liver, Kidney, CBC, Iron, Vitamins, Thyroid, Hormones)
- Summary cards with delta arrows for 8 key metrics
- Add Report modal with all metric fields
- Report history table with delete
- Responsive dark UI (Fraunces + DM Mono)

**Metrics tracked:** 50+ parameters across 9 body systems

---

## Blood Reports

---

### [Report] 2026-01-31 — Manipal Hospital, Old Airport Road

**Source:** Manipal Hospitals, Bengaluru  
**Type:** Routine Health Checkup

| Metric | Value | Status |
|---|---|---|
| Fasting Glucose | 97 mg/dL | ✅ Normal |
| Total Cholesterol | 177 mg/dL | ✅ Normal |
| Triglycerides | 137 mg/dL | ✅ Normal |
| HDL | 34.2 mg/dL | 🔴 Low |
| LDL | 127 mg/dL | ⚠️ Above optimal |
| VLDL | 27.4 mg/dL | ✅ Normal |
| Non-HDL | 142.8 mg/dL | ⚠️ Above optimal |
| TC:HDL Ratio | 5.18 | ⚠️ Borderline |
| SGOT | 72 U/L | 🔴 HIGH |
| SGPT | 59 U/L | 🔴 HIGH |
| ALP | 61 U/L | ✅ Normal |
| GGT | 30.3 U/L | ✅ Normal |
| Bilirubin Total | 0.36 mg/dL | ✅ Normal |
| Total Protein | 7.4 g/dL | ✅ Normal |
| Albumin | 4.6 g/dL | ✅ Normal |
| Uric Acid | 6.96 mg/dL | ✅ Normal |
| Vitamin D | 17.8 ng/mL | 🔴 DEFICIENT |
| Vitamin B12 | 272 pg/mL | ✅ Normal |
| TSH | 4.61 µIU/mL | ⚠️ Slightly above 4.25 |
| T3 | 1.15 ng/mL | ✅ Normal |
| T4 | 7.59 µg/dL | ✅ Normal |
| PSA | 0.30 ng/mL | ✅ Normal |

**Doctor notes (Manipal):** Vit D low, SGOT/SGPT mildly elevated, LDL 127.  
**Prescribed:** Cap Vit D3 60K × 1/week × 2 months, then 1/month × 6 months.  
**Follow-up:** SGOT/SGPT/CBC after 1 month. Fasting lipids + Free T4 + TSH after 3 months.

---

### [Report] 2026-05-29 — Tata 1mg Labs, Koramangala Bengaluru

**Source:** Tata 1mg Labs, Koramangala, Bengaluru  
**Type:** Comprehensive Silver Full Body Checkup + Cortisol + Infertility Panel

| Metric | Value | Status | vs Jan 2026 |
|---|---|---|---|
| Fasting Glucose | 79 mg/dL | ✅ Normal | ⬇️ Improved |
| HbA1c | 4.7% | ✅ Excellent | — (new) |
| Hemoglobin | 14.8 g/dL | ✅ Normal | — (new) |
| WBC | 7.71 K/µL | ✅ Normal | — (new) |
| Eosinophils | 8.8% | ⚠️ Mildly elevated | — (new) |
| ESR | 2 mm/hr | ✅ Excellent | — (new) |
| Serum Iron | 142 µg/dL | ✅ Normal | — (new) |
| TIBC | 311 µg/dL | ✅ Normal | — (new) |
| Total Cholesterol | 193 mg/dL | ✅ Normal | ⬆️ Slight rise |
| Triglycerides | 156 mg/dL | ⚠️ Borderline | ⬆️ Worsened |
| HDL | 35 mg/dL | 🔴 Low | → Unchanged |
| LDL | 127 mg/dL | ⚠️ Above optimal | → Unchanged |
| Non-HDL | 158 mg/dL | ⚠️ Above optimal | ⬆️ Worsened |
| TC:HDL Ratio | 5.5 | ⚠️ Borderline | ⬆️ Worsened |
| Creatinine | 0.88 mg/dL | ✅ Normal | — (new) |
| Uric Acid | 8.0 mg/dL | 🔴 HIGH | ⬆️ Worsened (was 6.96) |
| Chloride | 108.0 mmol/L | ⚠️ Slightly above | — (new) |
| SGOT | 32 U/L | ✅ Normal | ⬇️ MAJOR improvement |
| SGPT | 43 U/L | ✅ Normal | ⬇️ Improved |
| Vitamin D | 34.3 ng/mL | ✅ Sufficient | ⬆️ Fixed! |
| Calcium | 9.2 mg/dL | ✅ Normal | — (new) |
| Vitamin B12 | 185 pg/mL | 🔴 Below range | ⬇️ Dipped (was 272) |
| TSH | 4.72 µIU/mL | ✅ Normal (0.35–4.94) | ✅ Within wider range |
| T3 | 0.86 ng/mL | ✅ Normal | — |
| T4 | 7.3 µg/dL | ✅ Normal | — |
| Testosterone | 321 ng/dL | ✅ Normal | — (new) |
| FSH | 3.3 mIU/mL | ✅ Normal | — (new) |
| LH | 4.37 mIU/mL | ✅ Normal | — (new) |
| Prolactin | 29.11 ng/mL | 🔴 HIGH | — (new) |
| Cortisol (AM) | 13.0 µg/dL | ✅ Normal | — (new) |
| PSA | 0.30 ng/mL | ✅ Normal | → Unchanged |

**Key takeaways:**
- ✅ Liver fully recovered (SGOT/SGPT now normal)
- ✅ Vitamin D corrected by supplementation
- ✅ Blood sugar excellent (HbA1c 4.7%)
- 🔴 Uric acid risen to 8.0 — dietary intervention needed
- 🔴 Prolactin elevated at 29.11 — repeat fasting pooled sample needed
- ⚠️ Lipid pattern (low HDL, high LDL, rising Non-HDL) — needs continued focus
- 🔴 Vitamin B12 dipped below range — supplement recommended

---

*This changelog is maintained automatically. Each new report added to the dashboard is logged here.*

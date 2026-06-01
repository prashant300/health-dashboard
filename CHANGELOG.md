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

---

### [Body Composition Scans] — Accuniq Machine

Three body composition scans added from Accuniq BIA machine.

#### Aug 27, 2025 — Accuniq Scan

| Metric | Value | Status |
|---|---|---|
| Weight | 73.4 kg | ✅ Normal |
| Fat Mass | 16.8 kg | ⚠️ Above optimal |
| Body Fat % | 22.9% | ⚠️ Above 15–20% male range |
| Skeletal Muscle Mass | 31.7 kg | ⚠️ Slightly below target |
| BMI | 23.4 | ✅ Normal |
| Waist-Hip Ratio | 0.84 | ✅ Normal |
| BMR | 1592 kcal | ✅ Normal |
| ECW Ratio | 0.394 | ⚠️ Above optimal 0.38 |
| Body Type | Over fat | 🔴 |

#### Apr 26, 2026 — Accuniq Scan

| Metric | Value | Status | vs Aug 2025 |
|---|---|---|---|
| Weight | 73.5 kg | ✅ Normal | → Stable |
| Fat Mass | 16.7 kg | ⚠️ Above optimal | ↓ Slightly improved |
| Body Fat % | 22.7% | ⚠️ Above range | ↓ Slightly improved |
| Skeletal Muscle Mass | 31.9 kg | ⚠️ Building | ↑ +0.2 kg |
| BMI | 23.2 | ✅ Normal | → Stable |
| Waist-Hip Ratio | 0.85 | ✅ Normal | ↑ Slight rise |
| BMR | 1597 kcal | ✅ Normal | ↑ +5 kcal |
| ECW Ratio | 0.400 | ⚠️ Above optimal | ↑ Worsened |
| Body Type | Over fat | 🔴 | → Unchanged |

#### Jun 1, 2026 — Accuniq Scan

| Metric | Value | Status | vs Apr 2026 |
|---|---|---|---|
| Weight | 76.9 kg | ⚠️ Rising | ↑ +3.4 kg in 5 weeks 🔴 |
| Fat Mass | 19.4 kg | 🔴 High | ↑ +2.7 kg — significant jump |
| Body Fat % | 25.2% | 🔴 High | ↑ +2.5% — significant |
| Skeletal Muscle Mass | 32.2 kg | ✅ Growing | ↑ +0.3 kg ✅ |
| BMI | 24.3 | ✅ Normal (barely) | ↑ Rising toward overweight |
| Waist-Hip Ratio | 0.86 | ✅ Normal | ↑ Trending toward upper limit |
| BMR | 1613 kcal | ✅ Normal | ↑ +16 kcal |
| ECW Ratio | 0.392 | ⚠️ Above optimal | ↓ Slight improvement |
| Body Type | Over fat | 🔴 | → Unchanged |
| Fat to Lose to Target | 7.2 kg | 🔴 | ↑ Increased from 4.5 kg |

**Key insight Jun 2026:** 3.4 kg weight gain in 5 weeks with 2.7 kg being pure fat mass. Muscle continues growing (+0.3 kg) which is positive. Root cause likely sustained caloric surplus from frequent restaurant meals. This fat accumulation is the primary driver of high triglycerides (156), low HDL (35), and elevated uric acid (8.0) in blood reports. Fat loss of 7.2 kg target weight would likely normalise all three blood flags without medication.

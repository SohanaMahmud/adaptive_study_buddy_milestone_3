# Adaptive Study Buddy — Milestone 3
**INSE 6450: AI in Systems Engineering | Winter 2026 | Concordia University**

**Author:** Sohana Mahmud | PhD Student | ID: 40271073
**Submitted to:** Professor Ali Ayub, PhD | TA: Eeham Khan

---

## Repository Contents

| File | Description |
|------|-------------|
| `adaptive_study_buddy_milestone3.ipynb` | Main notebook — all code for M3 |
| `data.csv` | Synthetic dataset (300,000 rows, 5,000 users, 10,000 items) |
| `Milestone_3_Report.pdf` | Submitted report (PDF) |

**Generated outputs** (produced when notebook is run):
- `robustness_plots.png` — 6-panel robustness & calibration figure (In[14])
- `monitoring_dashboard.png` — 4-panel monitoring dashboard (In[18])
- `milestone3_artifacts.pt` — All 4 saved model states + version info
- `model_config_v3.txt` — Versioned config (features, scaler params, temperature)

---

## Quickstart — Google Colab (Recommended)

### Step 1 — Open the notebook
1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Click **File → Open notebook → GitHub**
3. Paste: `https://github.com/SohanaMahmud/adaptive_study_buddy_milestone_3`
4. Select `adaptive_study_buddy_milestone3.ipynb`

### Step 2 — Upload the data file
When **In[2]** runs, a file upload widget will appear. Upload `data.csv` from this repository (download it first from GitHub).

> ⚠️ The upload widget only works in an active browser session. If you restart the runtime, re-run In[2] and re-upload `data.csv`.

### Step 3 — Run all cells
- **Runtime → Run all** (or `Ctrl+F9`)
- Total runtime: approximately **5–7 minutes** on CPU (Colab free tier)
- No GPU required — the model runs on CPU in < 0.25 ms/sample

### Expected final output
```
✅ All model artifacts saved to milestone3_artifacts.pt
Version: v3.0
Dataset hash: 9fcba4a73a00
Models: original, retrained, incremental, jitter
Config saved to model_config_v3.txt
```



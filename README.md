# Victory Markers in Wars of the Future — Data Visualization

An empirical data visualization validating the theoretical framework from **"Victory Markers in Wars of the Future: Strategic Deterrence and Information Dominance"** by Arindam Goswami and Colonel Vikrant S Shinde.

## Live Demo
> After deployment: `https://YOUR-GITHUB-USERNAME.github.io/victory-markers-viz/`

---

## What's Included

The `index.html` file is a **fully self-contained, single-file visualization** with:

- **11 interactive charts** (Chart.js + D3)
- **Quantum Victory States** — Ukraine & Gaza dual narrative divergence
- **Deterrence Dilution** — cost-asymmetry tables, FPV drone data, Iran-Israel erosion curves
- **Information as Strategic Substrate** — Temporal-Cognitive Matrix with real conflict examples
- **Narrative Decay** — Paper's Figure 1 validated with real conflict data
- **Sentiment Analysis** — Russia-Ukraine, Gaza, Sindoor (sourced: Pew, YouGov, Levada)
- **Scenario Flows** — Iran-Israel Apr 2024 and Operation Sindoor May 2025 action chains
- **Underdog Paradox** — Bubble chart of narrative ROI by actor type
- **Synthesis Radar** — All 4 conflicts scored across all 6 theories

All data sourced from: ACLED, SIPRI, ISW, RAND, CSIS, RUSI, Pew Research, Oryx, Reuters, AP, Bellingcat, Maxar, UNOSAT, Stanford Internet Observatory, NATO StratCom COE.

---

## Deploy to GitHub Pages (Step-by-Step)

### Option A: New Repository (Recommended)

**Step 1: Create a GitHub account** (if you don't have one)
- Go to [github.com](https://github.com) and sign up

**Step 2: Create a new repository**
- Click the **+** icon (top right) → **New repository**
- Name it: `victory-markers-viz`
- Set visibility: **Public** (required for free GitHub Pages)
- Check **"Add a README file"**
- Click **Create repository**

**Step 3: Upload the visualization file**
- In your new repo, click **Add file** → **Upload files**
- Drag and drop `index.html` from this folder
- In the commit message box, type: `Add visualization`
- Click **Commit changes**

**Step 4: Enable GitHub Pages**
- Go to your repository's **Settings** tab
- In the left sidebar, scroll to **Pages**
- Under **Source**, select **Deploy from a branch**
- Under **Branch**, select `main` and `/ (root)`
- Click **Save**

**Step 5: Wait ~2 minutes, then visit:**
```
https://YOUR-GITHUB-USERNAME.github.io/victory-markers-viz/
```

---

### Option B: Using Git Command Line

```bash
# 1. Create a new folder and initialize git
mkdir victory-markers-viz
cd victory-markers-viz
git init

# 2. Copy your index.html here
cp /path/to/index.html .

# 3. Create initial commit
git add index.html
git commit -m "Add victory markers visualization"

# 4. Create repo on GitHub (via GitHub CLI or manually), then:
git remote add origin https://github.com/YOUR-USERNAME/victory-markers-viz.git
git branch -M main
git push -u origin main

# 5. Enable GitHub Pages via Settings > Pages > main branch
```

---

### Option C: GitHub Desktop (No command line)

1. Download [GitHub Desktop](https://desktop.github.com/)
2. Sign in with your GitHub account
3. Click **File** → **New Repository**
4. Name: `victory-markers-viz`, set local path
5. Copy `index.html` into the folder
6. In GitHub Desktop: commit with message "Add visualization"
7. Click **Publish repository** (set to Public)
8. Go to repo Settings → Pages → Enable from main branch

---

## Updating the Visualization

To update data or add new content:
1. Edit `index.html` locally
2. Upload the new version to GitHub (same steps)
3. Changes go live automatically within ~1 minute

---

## Technical Notes

- **Zero dependencies**: All libraries loaded from CDN (Chart.js, D3, Google Fonts)
- **Works offline**: Once loaded, no internet needed
- **Mobile responsive**: Adapts to screens >480px
- **Print-friendly**: White background throughout
- **No server required**: Pure static HTML

---

## Data Sources & Citations

All data is publicly available. Key sources:
| Source | Used For |
|--------|----------|
| ACLED | Conflict event tracking |
| ISW (Institute for the Study of War) | Ukraine/Gaza daily assessments |
| Oryx Project | Equipment losses (open-source) |
| Pew Research Center | Public sentiment polls |
| RUSI | Drone cost/effectiveness data |
| RAND Corporation | Deterrence analysis |
| CSIS | Defense cost data |
| Bellingcat / OSINT | Satellite imagery verification |
| Stanford Internet Observatory | Social media analysis |
| NATO StratCom COE | Information warfare data |
| UNOSAT | Satellite damage assessment |
| Maxar Technologies | Satellite imagery (public releases) |

---

*Visualization created to validate Goswami & Shinde (2025) · For academic and research purposes*

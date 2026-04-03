# HeBe Corporation - Brand Assets

Centralized asset repository for HeBe Corporation's logos, stamps, and signatures.  
Hosted via **GitHub Pages** for direct URL access across email signatures, KPI reports, dashboards, and documents.

---

## Quick Access

**Base URL:** `https://hebe-corporation.github.io/assets/`

| Asset | URL Path |
|-------|----------|
| Dr.Melaxin (black logo) | `logos/brands/dr_melaxin/dr_melaxin_black_transparent.png` |
| Dr.Melaxin (white logo) | `logos/brands/dr_melaxin/dr_melaxin_white_transparent.png` |
| HeBe VN (gold, black bg) | `logos/hebe/vietnam/hebe_vn_gold_black_bg.png` |
| HeBe VN (gold, transparent) | `logos/hebe/vietnam/hebe_vn_gold_transparent.png` |
| HeBe VN (gold, white bg) | `logos/hebe/vietnam/hebe_vn_gold_white_bg.png` |

**Usage example (HTML):**
```html
<img src="https://hebe-corporation.github.io/assets/logos/brands/dr_melaxin/dr_melaxin_white_transparent.png" alt="Dr.Melaxin" height="40">
```

**Usage example (Google Sheets):**
```
=IMAGE("https://hebe-corporation.github.io/assets/logos/brands/dr_melaxin/dr_melaxin_black_transparent.png")
```

---

## Repository Structure

```
assets/
├── README.md
├── logos/
│   ├── hebe/
│   │   ├── korea/
│   │   │   ├── hebe_korea_gold_black_bg.png
│   │   │   ├── hebe_korea_gold_transparent.png
│   │   │   └── hebe_korea_gold_white_bg.png
│   │   ├── vietnam/
│   │   │   ├── hebe_vn_gold_black_bg.png
│   │   │   ├── hebe_vn_gold_transparent.png
│   │   │   └── hebe_vn_gold_white_bg.png
│   │   └── cambodia/
│   │       ├── hebe_khmer_gold_black_bg.png
│   │       ├── hebe_khmer_gold_transparent.png
│   │       └── hebe_khmer_gold_white_bg.png
│   ├── brands/
│   │   ├── dr_melaxin/
│   │   ├── mary_and_may/
│   │   ├── unleashia/
│   │   ├── anua/
│   │   ├── medicube/
│   │   ├── dasique/
│   │   ├── medianswer/
│   │   ├── biodance/
│   │   └── aplb/
│   └── index.md
├── stamps/
│   └── hebe_korea_stamp.png
└── signatures/
    └── ceo_signature.png
```

---

## File Naming Convention

**Pattern:** `{brand}_{color}_{background}.png`

| Component | Values | Description |
|-----------|--------|-------------|
| `brand` | `hebe_korea`, `hebe_vn`, `hebe_khmer`, `dr_melaxin`, etc. | Entity or brand name (snake_case) |
| `color` | `gold`, `black`, `white`, `full_color` | Logo color variant |
| `background` | `transparent`, `black_bg`, `white_bg` | Background type |

**Examples:**
- `dr_melaxin_black_transparent.png` = Black logo, transparent background (for white/light backgrounds)
- `dr_melaxin_white_transparent.png` = White logo, transparent background (for dark backgrounds)
- `hebe_vn_gold_black_bg.png` = Gold logo on black background

**Image specs:**
- Logos: max 500px width, proportional height
- Stamps: 152 x 152px
- Format: PNG (transparency support)
- Color space: sRGB

---

## Brand Colors

| Brand | Primary | Secondary |
|-------|---------|-----------|
| HeBe Corporation | Champagne Gold `#C2A67D` | Warm Near-Black `#2A2522` |
| Dr.Melaxin | Clinical Teal `#3D8A9B` | Black `#1A1A1A` |

---

## Usage by Context

| Context | Logo Variant | Reason |
|---------|-------------|--------|
| KPI Email header (dark bg) | `dr_melaxin_white_transparent` | White logo visible on dark background |
| KPI Email footer (dark bg) | `hebe_vn_gold_black_bg` | Gold logo with its own dark background |
| Google Sheets dashboard | `dr_melaxin_black_transparent` | Black logo readable on white cells |
| HTML email signature | `hebe_vn_gold_transparent` | Adapts to any email client background |

---

## Adding New Assets

1. Prepare the logo in PNG format (max 500px width)
2. Create all 3 background variants if possible: `transparent`, `black_bg`, `white_bg`
3. Follow the naming convention: `{brand}_{color}_{background}.png`
4. Place in the appropriate `logos/brands/{brand_name}/` folder
5. Commit and push to `main` branch - GitHub Pages auto-deploys

---

## Related Repositories

| Repo | Purpose |
|------|---------|
| [hebe-hub](https://github.com/HeBe-Corporation/hebe-hub) | Email signature generator (GitHub Pages) |
| [assets](https://github.com/HeBe-Corporation/assets) | This repo - brand asset hosting |

---

*Maintained by HeBe Korea Corporation*

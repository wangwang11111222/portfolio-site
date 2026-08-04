# Portfolio Site

A responsive, employer-facing portfolio website hosted on GitHub Pages. Built with vanilla HTML/CSS — no frameworks, no build step, just clean static files.

## Deploy

### Option 1: Username Pages (recommended)

Rename this repository to `<github-username>.github.io`, then:

1. Go to **Settings** → **Pages**
2. Select **Deploy from a branch**
3. Choose the default branch and `/root`
4. The site will be live at `https://<github-username>.github.io/`

### Option 2: Project Pages

Keep any repository name, then:

1. Go to **Settings** → **Pages**
2. Select **Deploy from a branch**
3. Choose the default branch and `/root`
4. The site will be live at `https://<github-username>.github.io/<repo-name>/`

## Features

- **Hero section** with headline, summary, and key stats
- **Featured Work grid** — 13 projects with descriptions and technology tags
- **Selected Outputs** — chart thumbnails from quant strategies and factor models
- **Repository Hygiene** note explaining public-safe data practices
- **Fully responsive** — adapts from mobile to desktop with CSS Grid

## Projects Showcased

| Project | Stack | Description |
|---------|-------|-------------|
| ETF Volatility and Kelly Allocation | Python | HAR-YZ and EGARCH volatility forecasting with Kelly overlays |
| ETF Correlation Rotation | Python | Rotation strategy using signal state and rolling correlations |
| Cross-Sectional ETF Selection | Python | Ranking research with volatility, return features, and sweeps |
| Corporate Bond Structural Estimation | MATLAB/SAS/Python | Structural estimation, grid search, RL environment design |
| Alpha158 Factor Model | Python/LightGBM | Technical-factor generation and ML backtest research |
| Index NAV Verification | Python | Benchmark and NAV verification scripts with charts |
| Compiler | Java/ANTLR | Tiger compiler: lexer, parser, IR, data-flow, register allocation |
| Distributed Spanning Tree | Python | Topology definitions and STP convergence logs |
| Deep Learning Sequence Models | PyTorch | RNN, LSTM, Seq2Seq, Transformer, context distillation |
| HPC and HPCA Systems | C/CUDA | List ranking, funnel sort, branch prediction, cache coherence |
| Software Engineering | Java/Android | Android encryptor app and Java string utility with tests |
| Funnel Sort | C | Cache-oblivious k-way funnel sort implementation |
| PeatCode | Python/C++/LibTorch | LSTM-based stock prediction pipeline with backtesting |

## File Structure

```
portfolio-site/
├── index.html      # Main HTML with 13 project cards
├── styles.css      # Responsive CSS (CSS variables, Grid, media queries)
├── assets/         # Chart thumbnails (PNG)
└── README.md
```

## Customization

To add or edit projects, modify the `<article class="project">` blocks in `index.html`. Each card supports:

- `<h3>` — project title
- `<p>` — one-line description
- `<div class="tags">` — technology tags

To update chart images, replace files in `assets/` and update the `<img>` `src` attributes.

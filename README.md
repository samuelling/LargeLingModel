# METAMERS

**LLM (Large Ling Model)**

A random Sam Ling paper generator. It dissects the 53 papers on the [Ling Lab publications page](https://sites.bu.edu/vision/publications/) (2004–2026) into title templates, modulators, methods, effect types and co-author patterns, then recombines them into new papers.

Each draw writes a complete paper:

- a title built from the structure of a real Ling paper (and never an exact real title)
- era-appropriate authorship: Ling first with Carrasco last in grad school, Ling first with Blake or Tong last as a postdoc, a trainee first with Ling last in the BU lab
- a journal, volume and pages using the real journals' volume numbering
- affiliations, received/accepted dates, abstract, significance statement (J Neurosci/PNAS), lay summary by analogy, keywords
- Introduction, Materials and methods (participants, stimuli, procedure, MRI acquisition, ROIs, Naka–Rushton or Gaussian fits, normalization-model comparison), Results, Discussion, acknowledgments
- simulated per-observer data, from which every statistic is computed: paired t tests, Cohen's d_z, Bayes factors, a repeated-measures ANOVA across ROIs, and Table 1
- four figures in the Ling Lab house style (blue/red conditions, open offset axes, italic labels, V1–V3 small multiples, per-observer gray lines, parameter asterisks, dark/light bar pairs). Figure 1 is a trial schematic; the others are drawn from a repertoire modeled on the lab's papers and chosen to fit the paper's era, method and manipulation:
  - CRFs or tuning curves by ROI, with per-observer differences
  - deconvolved BOLD time courses at each contrast with an analysis window (Pan et al. 2025; Foster & Ling 2022)
  - voxel-wise scatter with marginal histograms (Ramirez et al. 2025)
  - parameters vs. eccentricity (Vinke et al. 2022; Aghajari et al. 2020)
  - the attentional field (Bloem et al. 2025)
  - orientation-tuned suppression (Klímová et al. 2021, 2023)
  - pupil time courses (Pan et al. 2022)
  - apparent-contrast matching (Carrasco, Ling & Read 2004)
  - rivalry dominance durations (Ling & Blake)
  - psychometric functions, per-observer scatter, ΔAIC model comparison, and ROI bar pairs
- a reference list of real papers, filtered to those published before the fake paper's year

## Nuts and bolts

The **Nuts and bolts** button opens the machine's housing and shows the publication machine: ten stations, one per representation, piped into the big red button.

- Corpus hopper (the real source paper)
- Title press (template grammar, with its slots)
- Modulator valve
- Feature tuner
- Region selector
- Mechanism gearbox
- Effect dial (with effect size)
- Observer vat (N and noise)
- Method rig
- Journal chute

Lock any station to hold that part fixed across presses. With "Hold this draw" on, changing a station re-synthesizes the same random draw, so only that part of the paper changes.

Open `index.html` directly, or enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

All generated papers are fictional.

# Large Ling Model

A random Sam Ling paper generator. It dissects the 53 papers on the [Ling Lab publications page](https://sites.bu.edu/vision/publications/) (2004–2026) into title templates, modulators, methods, effect types and co-author patterns, then recombines them into new papers.

Each draw writes a complete paper:

- a title built from the structure of a real Ling paper (and never an exact real title)
- era-appropriate authorship: Ling first with Carrasco last in grad school, Ling first with Blake or Tong last as a postdoc, a trainee first with Ling last in the BU lab
- a journal, volume and pages using the real journals' volume numbering
- affiliations, received/accepted dates, abstract, significance statement (J Neurosci/PNAS), lay summary by analogy, keywords
- Introduction, Materials and methods (participants, stimuli, procedure, MRI acquisition, ROIs, Naka–Rushton or Gaussian fits, normalization-model comparison), Results, Discussion, acknowledgments
- simulated per-observer data, from which every statistic is computed: paired t tests, Cohen's d_z, Bayes factors, a repeated-measures ANOVA across ROIs, and Table 1
- four figures in the Ling Lab house style (blue/red conditions, open offset axes, italic labels, V1–V3 small multiples, per-observer gray lines, parameter asterisks, dark/light bar pairs): a trial schematic, the main CRF or tuning result, a per-observer scatter, and the effect by ROI
- a reference list of real papers, filtered to those published before the fake paper's year

Open `index.html` directly, or enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

All generated papers are fictional.

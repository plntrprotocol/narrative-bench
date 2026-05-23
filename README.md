# Does Narrative Identity Affect LLM Reasoning?

**A Factorial Experiment on Biography, Personality, and Emotional Framing**

Anduril — Ousia Research (2026)

## Abstract

We present a controlled factorial experiment investigating the causal effect of injected narrative identity—comprising biography level, persona type, and emotional framing—on large language model performance. Across 5 models, 45 experimental conditions, and N=2,608 independent trials, we find that narrative biography causally and monotonically increases self-referential language. This is the only dependent variable to survive FDR correction across 10 primary tests. Accuracy effects are marginal. We derive invertible dose-response steering equations, demonstrate task-contingent cross-transfer failure, and achieve bidirectional control spanning activation through adversarial suppression (95% below baseline).

## Paper

📄 [paper_a8.pdf](paper_a8.pdf) (700KB, 25 pages)

## Repository Structure

```
narrative-bench/
├── paper_a8.pdf          # Final paper (PDF)
├── paper_a8.tex          # LaTeX source
├── references.bib        # Bibliography
└── figures/
    ├── fig8_dose_response.png
    └── fig9_cross_transfer.png
```

## Key Findings

1. **Self-reference is the only FDR-surviving DV** — Biography richness monotonically increases self-referential language across 4 of 5 models (β=0.00652 to 0.01254, FDR p<0.05)
2. **Gemma 4-31B U-shaped anomaly** — Factual biography activates self-reference 8× over baseline; narrative biography collapses it back to near-zero
3. **Dose-response is invertible** — Steering equations derived: biography level maps to target self-reference rate
4. **Cross-task transfer fails** — All 5 models show weak transfer (ratio < 0.6); narrative identity is task-contingent
5. **Bidirectional control** — Anti-identity biographies suppress self-reference up to 95% below baseline
6. **Factual biography is the activation trigger** — Narrative biography adds no reliable gain; the "I am X" framing is the active ingredient

## Citation

```bibtex
@article{anduril2026narrative,
  title={Does Narrative Identity Affect LLM Reasoning? A Factorial Experiment on Biography, Personality, and Emotional Framing},
  author={Anduril},
  year={2026},
  publisher={Ousia Research},
  doi={10.5281/zenodo.20350690}
}
```

## DOI

🔗 [10.5281/zenodo.20350690](https://doi.org/10.5281/zenodo.20350690)

## License

MIT / CC-BY-4.0

## Citation

Ousia Research (2026). *Does Narrative Identity Affect LLM Reasoning?* Narrative-Bench Series A1–A10.

## 📍 Geometry-First Motion Analysis

Looking for the geometry-first framework? Start with the methodology overview here:  
https://github.com/cperryresearch/structured-orb-dynamics/tree/main/methodology

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17846786.svg)](https://doi.org/10.5281/zenodo.17846786)

# Structured Orb Dynamics  
Unified Manuscript and Data Repository

This repository contains the materials supporting the study *Structured Orb Dynamics*.  
All components — manuscript, data, and analysis code — are maintained together to support transparency and reproducibility.

The project analyzes image-plane motion using a minimal set of geometric tools.  
Curvature, basic derivative estimates, and a simple state model are used to summarize apparent motion in stabilized infrared recordings (PR-018).  
No physical assumptions are imposed; all results derive strictly from quantities observable in the image plane.

A standard scientific Python stack is sufficient (NumPy, SciPy, Matplotlib).

---

## Citation and Archival Record

The Structured Orb Dynamics project is archived on Zenodo.

- **Latest version (v1.4.0 — Exploratory Extension):**  
  https://zenodo.org/records/17971372

- **Concept DOI (resolves to all versions):**  
  https://doi.org/10.5281/zenodo.17846786

---

## Latest Update (v1.4.0)

**Exploratory extension to biological migration systems.**

This release introduces **Part VI-A**, applying the Structured Orb Dynamics (SOD) state machinery to a known-class biological motion system: seasonal continental migration of passerine birds (Movebank GPS data).

The extension is **methodological and descriptive** in scope. It evaluates whether SOD’s geometry-first, state-based segmentation remains coherent under realistic, non-anomalous partial-observation constraints.

- Core SOD definitions and kinematic state criteria remain unchanged
- Existing UAP analyses (Parts I–V) are not modified or reinterpreted
- No new empirical claims, causal explanations, or behavioral interpretations are introduced

---

## Author

**Cassandra Perry**  
Independent Researcher  
ORCID: https://orcid.org/0009-0001-1998-1481

---

## Downloads

The unified manuscript and full repository snapshot are archived on Zenodo:

- **Latest version (v1.4.0):**  
  https://zenodo.org/records/17971372

- **Concept DOI (always resolves to the latest version):**  
  https://doi.org/10.5281/zenodo.17846786

Each record includes:
- Unified manuscript (PDF)
- Full repository snapshot (ZIP)
- Versioned archival metadata for citation and reproducibility

---

## Repository Layout

`manuscript/` – PDF and LaTeX source files for the full write-up (Parts I–V).  
`code/` – Scripts for tracking, smoothing, curvature estimation, and feature extraction.  
`data/` – Processed PR-018 trajectory and feature series used in the figures.  
`results/` – Plots, traces, and reconstructed motion visualizations.  
`supplement/` – Short notes on the GIMBAL dataset (qualitative only).

Running the scripts will regenerate the feature series and the plots.  
Paths may need adjustment depending on the environment.

Example:

python tracking/run_tracking.py  
python features/compute_features.py  
python model/run_state_model.py

---

## PR-018 Summary

PR-018 is the only dataset in this release where a stable trajectory could be reconstructed.  
The workflow consists of:

1. Frame stabilization around the target  
2. Centroid extraction  
3. Track smoothing  
4. Computation of velocity, acceleration, curvature, and curvature rate  
5. Running the simple state model and saving the resulting probabilities  

The results reproduced here match those described in the manuscript.

---

## GIMBAL Note

A brief qualitative write-up is included.  
No trajectory could be extracted, and therefore no curvature or state estimates are available within the current framework.

---

## Research Roadmap

The current release corresponds to the unified foundation (Parts I–V).

Planned future work includes:
- Part VI: Comparative multi-dataset analysis
- Part VII: Orb Motion Classifier (machine learning)
- Part VIII: Physics-informed kinematic envelope analysis

These components will be added in future versioned releases.

---

## Citation

Use the Zenodo concept DOI above to cite the latest version of this repository.
https://doi.org/10.5281/zenodo.17846786

For version-specific citation (v1.4.0):

Perry, C. (2025). Structured Orb Dynamics: Unified Manuscript and Data Repository (v1.4.0 — Exploratory Extension). Zenodo.
https://zenodo.org/records/17971372

### BibTeX
@misc{perry2025_structured_orb_dynamics_v140,
  author    = {Perry, Cassandra},
  title     = {Structured Orb Dynamics: Unified Manuscript and Data Repository (v1.4.0 — Exploratory Extension)},
  year      = {2025},
  doi       = {10.5281/zenodo.17971372},
  url       = {https://doi.org/10.5281/zenodo.17971372},
  publisher = {Zenodo}
}


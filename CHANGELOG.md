# Changelog

All notable changes to this project will be documented in this file.  
The format follows [Semantic Versioning](https://semver.org/).

---

## [1.2.0] – 2025-12-08
### Added
- Full **Part III — Motion-State Classifier** (state definitions, observation model, likelihood formulation, transition model, posterior inference, and implementation outline).
- Full **Part IV — PR-018 Deep Analysis**, including:
  - Trajectory reconstruction summary
  - Curvature and feature extraction
  - State probability results
  - Posterior interpretation, consistency assessment, and failure modes
  - Formal summary of the PR-018 geometric behavior
- **GIMBAL Supplementary Analysis** (qualitative observations, no quantitative results).
- **Numerical Stability and Error Propagation** section in Part II.
- **Geometric Limits** section in Part II.
- Standardized figure environments (`\orbfig`, `\orbfigwide`) across the manuscript.
- **Author Contributions** section.
- **CITATION.cff** for formal citation metadata.
- **Download links** (PDF and ZIP) added to README for v1.2.0.
- Zenodo DOI badge for version release.

### Changed
- Repository structure organized into four formal manuscript parts.
- Renamed former "Part III" to **Part IV** to reflect final structure.
- Updated README to reflect the v1.2.0 release, including corrected DOI references.
- Improved manuscript consistency (labels, section numbering, cross-references).
- Polished abstract, introduction, and framework descriptions for clarity and formal tone.

### Fixed
- Overfull and underfull box warnings in LaTeX.
- Incorrect references to figure macros (`\orbfigwide`).
- Duplicate DOI badge display in README.
- Misaligned Part numbering across main.tex and manuscript tree.

---

## [1.1.0] – 2025-12-07
### Added
- Initial unified manuscript (Parts I–II).
- Curvature model, discrete estimator, smoothing methods.
- Bootstrap-based uncertainty discussion.
- Preliminary PR-018 trajectory and curvature plots.
- Initial PR-018 state model output.
- README overview and project structure.
- Zenodo DOI and GitHub integration.

---

## [1.0.0] – 2025-12-06
### Added
- Repository created.
- Initial code for trajectory extraction, smoothing, and feature computation.
- First draft of manuscript scaffold.

# Contributing to Structured Orb Dynamics

Thank you for your interest in contributing to the Structured Orb Dynamics project.  
This repository accompanies the research manuscript and provides deterministic, geometry-first tools for reconstructing trajectories and analyzing motion using image-plane data.

The goal of all contributions is to maintain:
- Clarity of geometric definitions  
- Reproducibility of all figures and classifier outputs  
- Strict separation between image-plane inference and any physical/speculative claims  
- Academic transparency and falsifiability  

Please review the guidelines below before opening an issue or submitting a pull request.

---

## 1. Scope of This Project

This project focuses on:
- Geometry-first motion analysis  
- Image-plane trajectory reconstruction  
- Curvature, angular change, and proportional inference  
- Reproducibility through open-source code and deterministic pipelines  

This project does **not** attempt to:
- Estimate physical range, velocity, or size  
- Perform platform or sensor calibration  
- Interpret the physical nature of observed objects  
- Make claims beyond what follows directly from image-plane geometry  

Issues or discussions that extend outside of this scope will be marked with the `scope` label and may be closed for focus.

---

## 2. Opening Issues

Before opening a new issue, please check whether a similar discussion already exists.

When opening a new issue, please:
- Use the appropriate label (`reproducibility`, `clarity`, `geometry`, `classifier`, or `documentation`)  
- Keep feedback concise and focused on a specific section, definition, figure, or function  
- Avoid speculation; restrict comments to geometry, code behavior, and reproducible results  

If reporting a reproducibility concern:
- Include the exact command(s) used  
- Note your environment (Python version, OS, etc.)  
- Attach or summarize the output difference you observed  

Pinned Issue #1 provides project scope and engagement guidelines.

---

## 3. Pull Requests

Pull requests are welcome for:
- Improving clarity of documentation  
- Adding small reproducibility improvements  
- Fixing true inconsistencies in geometric definitions or classifier behavior  
- Enhancing code readability or determinism  

Pull requests **should not** introduce:
- Physical assumptions  
- Speculative interpretations  
- Unverifiable claims or non-deterministic behavior  

Before submitting a pull request:
1. Ensure the change is within project scope  
2. Document all modifications clearly  
3. Ensure all figures or outputs remain reproducible  

---

## 4. Coding Standards

- Follow existing file and module structure  
- Keep functions minimal, deterministic, and explicit  
- Avoid adding dependencies unless strictly necessary  
- Prefer NumPy and simple Python tools over large frameworks  
- Maintain reproducibility for all outputs  

---

## 5. Community Conduct

Please maintain a respectful, academic tone.  
The goal of this repository is to provide transparent, falsifiable, geometry-based analysis tools for the research community.

Contributions that uphold clarity, reproducibility, and rigor are greatly appreciated.

---

Thank you for contributing to the Structured Orb Dynamics project!

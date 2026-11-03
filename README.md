# TrustInspect Reviewer Simulation

[![Launch simulation](https://img.shields.io/badge/Launch-Interactive%20Simulation-2f6fa3)](https://pratikpatelresearch.github.io/TrustInspect-simulation/)
[![Main implementation](https://img.shields.io/badge/Main-TrustInspect%20Repository-142331)](https://github.com/pratikpatelresearch/TrustInspect)

A static, interactive reviewer demonstrator for **TrustInspect**, an auditable and risk-aware industrial anomaly-inspection framework.

## Reviewer experience

The simulation lets reviewers:

- choose among eight representative accepted cases from VisA, MVTec AD, MVTec LOCO AD, and MVTec AD 2 Public;
- run the full TrustInspect pipeline or select the visual-evidence, semantic-inspection, or verification-and-risk agent;
- inspect staged agent traces and PASS, FAIL, HUMAN REVIEW, or ABSTAIN dispositions;
- explore frozen dataset evidence, explainability overlays, A100 resource measurements, and audit boundaries;
- complete a blinded human-review worksheet and export ratings locally as JSON.

## Scientific boundary

This site replays frozen accepted artifacts for reviewer interaction. It does **not** execute live model inference, generate new experimental measurements, establish detector-level SOTA superiority, or constitute a completed real-participant human study. Human ratings remain in the reviewer’s browser unless they explicitly export them.

## Links

- **Live simulation:** https://pratikpatelresearch.github.io/TrustInspect-simulation/
- **Main implementation:** https://github.com/pratikpatelresearch/TrustInspect

## Contents

The repository contains only the static HTML, CSS, JavaScript, and eight representative visualization assets required by the simulation. Datasets, model weights, private logs, credentials, and mutable research checkpoints are excluded.

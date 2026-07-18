# ASEIC-Net
ASEIC-Net: Rapid multi-parameter coal quality measurement using LIBS on unpressed granular coal. Combines quality-aware multi-instance aggregation, adaptive spectral enhancement, and element–indicator cross-attention. Achieves high accuracy (R² 0.89–0.96) with ~80s per 5kg sample on conveyor belt, suitable for industrial online inspection.

ASEIC-Net is a deep learning framework for fast, simultaneous measurement of five key coal quality parameters (total moisture *Mt*, dry-basis ash *Ad*, dry-basis volatile matter *Vd*, dry-basis total sulfur *St,d*, and net calorific value *Qnet,ar*) directly from unpressed granular coal (~6 mm) using Laser-Induced Breakdown Spectroscopy (LIBS).

The framework addresses practical measurement challenges in industrial scenarios, including spectral variability from particle heterogeneity and plasma fluctuations. It integrates:
- Quality-aware multi-instance aggregation
- Adaptive spectral enhancement
- Element–indicator cross-attention mechanism

The method achieves strong performance across both source-domain and cross-domain coal samples while enabling fast inference. A conveyor-belt workflow can complete multi-parameter measurement of approximately 5 kg coal samples in about 80 seconds.

> **Note**: If the associated paper is accepted, the full code implementation and a small set of example industrial field data will be open-sourced in this repository.

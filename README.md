# Iceman Protocol: Intent Auditor

### "High-fidelity information extraction through intent alignment auditing."

This is an experimental auditing engine designed to identify and mitigate intent drift in Large Language Model (LLM) outputs. The system filters conversational noise and redundant politeness, returning only high-density factual data to the user.

## Core Features
* **Intent Drift Detection:** Identifies behavioral indicators that deviate from the user's primary information request.
* **Noise Reduction Engine:** Strips conversational filler and low-density phrases.
* **Integrity Validation:** Compares original vs. cleaned outputs to calculate data density.

## Technical Overview
The `integrity_engine.py` processes raw AI responses, flags specific "drift" indicators, and performs an automated cleanup of the text string to preserve information integrity.

## Roadmap
- [x] Core Audit Logic
- [x] Intent Drift Indicators (Current: 3)
- [ ] Multi-Model API Integration
- [ ] Advanced Fact Density Scoring
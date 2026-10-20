# Ryan F. McCullough

Systems engineering for AI early warning in the neonatal ICU.
Senior Vice President of Solutions Engineering at an enterprise analytics SaaS company serving highly regulated industries. Doctor of Engineering, The Pennsylvania State University (praxis defended September 2026).

[ryanfmccullough.com](https://ryanfmccullough.com) · [LinkedIn](https://www.linkedin.com/in/ryanfmccullough) · [ORCID](https://orcid.org/0009-0005-4107-1408) · [Google Scholar](https://scholar.google.com/citations?user=sXjEz3kAAAAJ) · [hello@ryanfmccullough.com](mailto:hello@ryanfmccullough.com)

## Research

A model's risk score only matters once decision logic turns it into delivered alerts, and that step is where clinical AI usually succeeds or fails. My doctoral work builds an evaluation harness that holds the alerting logic fixed so candidate architectures can be compared on what they cost clinicians (alarm burden) and what they buy patients (warning time). Two backbones with matching discrimination produced alert streams that differed by a factor of 2.1 in candidate volume and 110 minutes in median warning time, which is the comparison the harness exists to make.

Working interests: AI verification and validation, workload-aware clinical decision support, physiologic time-series modeling, self-supervised learning, alarm governance, and reproducible engineering evidence packages.

## Publications and talks

- McCullough, R. F., Krall, A., & McCullough, K. (2026). Designing AI-enabled neonatal early-warning systems with backbone-agnostic self-supervised learning. *Proceedings of the IISE Annual Conference & Expo 2026.*
- McCullough, R. F. (2026). *Beyond prediction: Designing workload-aware AI early warning for the neonatal intensive care unit.* Doctor of Engineering praxis, The Pennsylvania State University.
- McCullough, R., & Krall, A. (2026, February). Smarter early-warning for newborns: Reducing delays and alarm fatigue in the NICU. IISE Healthcare Systems Process Improvement Conference, Atlanta, GA.

## Code

The praxis codebase is private while technology-transfer questions are settled. Public projects on open physiologic datasets:

- [ecg-calibration-ptbxl](https://github.com/ryanfmccullough/ecg-calibration-ptbxl): calibrated ECG classification on PTB-XL. Trains a compact baseline, then reports what the accuracy number leaves out: expected calibration error before and after temperature scaling, and an operating-point table of alerts per 100 recordings against sensitivity. Scaffold and tests complete; baseline results in progress.

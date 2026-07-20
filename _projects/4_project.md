---
layout: page
title: Mobile ML Model Leakage
description: Automated program analysis for protecting on-device machine-learning models.
img:
importance: 4
category: research
related_publications: true
---

Mobile applications frequently embed valuable machine-learning models in native binaries. I investigated how reverse engineering can identify model-loading and decryption logic and expose protected model artifacts.

I developed an automated leakage-detection framework combining symbolic execution, data-flow analysis, and cryptographic reasoning to recover protection workflows and detect exploitable leakage. {% cite zhu2025modelleakage %}

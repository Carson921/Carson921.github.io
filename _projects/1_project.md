---
layout: page
title: Security of Agentic Browsers
description: Systematic analysis and red-teaming of browser-based LLM agents.
img:
importance: 1
category: research
related_publications: true
---

Agentic browsers combine language-model reasoning with access to webpages, credentials, and high-impact browser actions. My work studies how indirect, implicit, and direct prompt injection can exploit this combination.

Across commercial and open-source systems, I investigated attacks using hidden content, malicious iframes, and hidden forms to manipulate agent actions, forge clicks, and leak private browser context. This work also explores visibility-aware, provenance-aware, and tool-layer defenses. {% cite zhu2026browsers %}

At Samsung Research America, I extended this direction through red-teaming, mitigation development, agent-harness components, and security benchmarks with fine-grained stepwise and trajectory-level evaluation.

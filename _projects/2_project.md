---
layout: page
title: Memory Security of LLM Agents
description: Access-control attacks and defenses for agents with long-term memory.
img:
importance: 2
category: research
related_publications: true
---

Long-term memory improves an agent's ability to work across interactions, but it also creates a new security boundary. I proposed **FragFuse**, a black-box attack that distributes prohibited intent across separate interactions and reconstructs that intent through memory retrieval.

The attack was evaluated across four agent domains and multiple state-of-the-art guardrails. It achieved substantially higher access-control bypass effectiveness than existing baselines while preserving the agent's ability to complete the original target task. {% cite zhu2026fragfuse %}

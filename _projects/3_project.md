---
layout: page
title: Jailbreaking Online LLM Services
description: Special-token attacks against real-world chatbot and API services.
img:
importance: 3
category: research
related_publications: true
---

**MetaBreak** is a systematic jailbreak method against online LLM services. It exploits model-inherent special tokens to manipulate chat templates and simultaneously bypass internal safety alignment, platform-added conversation wrappers, and external content moderation.

The work introduces four attack primitives - response injection, turn masking, input segmentation, and semantic mimicry - and evaluates them across four open-source LLMs and seven real-world chatbot and API services. {% cite zhu2026metabreak %}

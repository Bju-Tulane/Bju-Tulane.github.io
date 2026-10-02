---
layout: page
title: research
permalink: /research/
description: My research studies how LLMs and LLM-based multi-agent systems fail under attack, and how machine learning can make software analysis more secure.
nav: true
nav_order: 1
---

## Overview

Large language models are no longer used only as chatbots. They now write code, test apps, and act as agents that make decisions together. This creates new security risks: an aligned model can be jailbroken, a group of cooperating agents can be manipulated, and AI-assisted tooling can be used to hide malicious code. My research aims to **understand these failures systematically and to build tools that detect and measure them**.

---

## Current Directions

### Security of LLM Multi-Agent Systems

As LLM agents are increasingly deployed in groups that must coordinate and reach decisions together, the security of the group becomes as important as the safety of any single model. I study how multi-agent LLM systems can fail under adversarial conditions and how their robustness can be evaluated in a principled way.

### Jailbreaks and Alignment Evaluation

I am interested in why aligned LLMs remain vulnerable to jailbreak attacks, and in moving from ad-hoc red teaming toward more systematic and reproducible ways of evaluating model alignment.

---

## Past Work at the University of Cincinnati

### JSWasM: JavaScript Behavior Modeling and Policy Enforcement

Attackers increasingly hide malicious JavaScript behind WebAssembly and AI-assisted obfuscation. I developed **JSWasM**, a WebAssembly-aware JavaScript sandbox for runtime behavioral analysis of obfuscated malware. It introduces a hybrid static–dynamic detection approach that uncovers obfuscation and evasion tactics that purely static tools miss.
Related paper: [_A Novel Runtime Monitoring Framework for WebAssembly-Obfuscated Malicious JavaScript Classification_](https://www.techrxiv.org/doi/abs/10.36227/techrxiv.176115871.16121085) (TechRxiv preprint).

### OLLM: LLM-Powered Verification for Android Apps

Many app bugs never crash; the app simply does the wrong thing. I developed **OLLM**, which integrates multimodal LLM reasoning into a verification pipeline that combines UI flows, API sequences, and task context to detect these non-crash functional bugs. The system improved detection accuracy by about **50%** over the baseline.
Related papers: _APSEC 2024_ and _FineChain_ (preprint).

### Provenance and Reproducibility in Scientific Workflows

I investigated data provenance and security in scientific workflows, and designed provenance-driven debugging pipelines for anomaly detection and reproducibility.

---

For the full list of papers, see my [publications](/publications/).

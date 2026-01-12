# World Models & Predictive Coding

**Key Paper:** World Models  
**Author:** David Ha  
**Year:** 2018  
**arXiv:** https://arxiv.org/abs/1803.10122

**Related Concept:** Predictive Coding (Friston et al.)

---

## Summary

World Models propose learning a **compact internal model of the environment** that enables agents to:
- Predict future states
- Plan actions internally
- Reduce reliance on direct interaction

The approach combines:
- Representation learning (latent states)
- Dynamics modeling
- Policy learning within learned simulators

Predictive Coding extends this idea by framing intelligence as **minimization of prediction error**.

---

## Industrial AI Relevance

World models are foundational for:
- Digital twins
- What-if simulation
- Planning under uncertainty
- Fault anticipation

They align naturally with physics-based modeling.

---

## Industrial AI Lens

✅ Strengths:
- Enables planning without acting
- Reduces data requirements
- Compatible with hybrid physics + ML models

⚠️ Challenges:
- Model mismatch can cause catastrophic decisions
- Requires continuous validation
- Needs uncertainty quantification

➡️ In Industrial AI, world models must be **constrained, monitored, and hybridized** with first-principles models.
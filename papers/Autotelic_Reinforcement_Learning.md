# Autotelic Reinforcement Learning

**Title:** Autotelic Reinforcement Learning  
**Authors:** Cédric Colas et al.  
**Year:** 2020  
**arXiv:** https://arxiv.org/abs/2007.08406

---

## Summary

Autotelic Reinforcement Learning introduces the idea of **self-generated goals** driven by intrinsic motivation rather than externally specified reward functions. Agents autonomously propose, explore, and learn goals that maximize learning progress.

Key ideas:
- Goal-conditioned policies
- Intrinsic motivation via learning progress
- Curriculum learning emerging from exploration
- Decoupling task discovery from task execution

---

## Industrial AI Relevance

Autotelic RL is valuable for **simulation-heavy industrial domains** where:
- Explicit reward design is difficult
- Tasks evolve over time
- Exploration must precede optimization

However, **pure autotelic behavior is unsafe** in real industrial systems.

---

## Industrial AI Lens

✅ Useful for:
- Simulation-based skill acquisition
- Pretraining in digital twins
- Discovering operational regimes

⚠️ Limitations:
- No built-in safety guarantees
- Requires strict constraints before deployment
- Not suitable for direct closed-loop control

➡️ In Industrial AI, autotelic RL belongs **inside simulators**, not on real assets.
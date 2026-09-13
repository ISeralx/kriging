# Multi-Agent Kriging

### Interactive spatial interpolation, driven by a team of sampling agents

Kriging is the geostatistician's interpolator: given a handful of measurements of an unknown
spatial field, it produces the **best linear unbiased prediction** at every other point — *and*
a map of its own uncertainty — by modelling the field as a Gaussian process with a fitted
covariance (variogram).

This demo puts that idea in motion: **multiple agents** explore a domain, sample the field, and
the kriging surface (mean **and** variance) updates live as their measurements come in. Watching
the uncertainty map collapse where the agents have been — and stay wide where they haven't — is
the whole intuition behind information-driven sampling.

**▶ Live demo:** https://iseralx.github.io/kriging/

## What you can see

- The **predicted field** (kriging mean) rebuilt from scattered samples.
- The **uncertainty map** (kriging variance) — high where data is sparse, low near samples.
- **Agents** moving and sampling, so you can watch the estimate and its error evolve.

## Background

Companion visualisation to my **BSc thesis (Physics)** on multi-agent kriging — using the
kriging variance as a signal to decide *where a team of agents should sample next*.

---

*Alejandro Soler Gonzálvez · [portfolio](https://iseralx.github.io/ISeralx/)*

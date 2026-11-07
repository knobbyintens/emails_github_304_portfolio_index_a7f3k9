---
title: "Neurocast Engine: Streaming Time-Series Forecasting at the Edge"
collection: showcase
status: "under review"
date: 2025-05-12
summary: "A compact Transformer-based forecaster for short-horizon demand prediction on constrained edge hardware."
tags:
  - forecasting
  - edge
  - transformers
permalink: /showcase/neurocast-engine
---

Neurocast targets the practical case of minute-level demand signals arriving from hundreds of sensors. The engine keeps a sliding window of recent observations, runs a quantised encoder at the edge, and emits forecasts with calibrated uncertainty bands. Field trials on two retail deployments reduced forecast error against the prior seasonal baseline while staying inside a 40 MB memory budget.

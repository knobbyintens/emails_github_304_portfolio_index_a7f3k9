---
title: "Streamforge: Declarative Streaming ETL for Messy Event Data"
collection: showcase
status: "pending review"
date: 2025-06-03
summary: "A declarative pipeline layer that turns long-lived, schema-drifting event streams into typed, queryable tables."
tags:
  - streaming
  - etl
  - data-engineering
permalink: /showcase/streamforge-pipeline
---

Streamforge lets analysts describe transformations in a small configuration dialect and compiles them into fault-tolerant stream jobs. It tracks schema drift, backfills late events, and exposes the result as an append-only table that downstream dashboards can consume. The reference implementation ships connectors for the common message brokers used in our internal stack.

---
title: "Policy Scan: Automated Open-Source Licence Auditing for Monorepos"
collection: showcase
status: "published"
date: 2024-11-20
summary: "A static analyser that inventories third-party dependencies in large monorepos and flags licence obligations that conflict with the project's distribution policy."
tags:
  - licensing
  - compliance
  - static-analysis
permalink: /showcase/policy-scan
repository: "https://github.com/knobbyintens/policy-scan-emails304"
---

Policy Scan crawls lockfiles, vendored source trees and container manifests, then resolves each package to an SPDX licence identifier. Rules map the discovered licences to the obligations of the host project and produce a review report grouped by owning team. The tool is used in CI to block merges that introduce incompatible licences.

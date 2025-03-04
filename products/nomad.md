---
title: Nomad
layout: post
permalink: /nomad
iconSlug: "NA"
category: server-app
link: https://support.hashicorp.com/hc/en-us/articles/360021185113-Support-Period-and-End-of-Life-EOL-Policy
sortReleasesBy: "releaseCycle"
changelogTemplate: https://github.com/hashicorp/nomad/blob/v__LATEST__/CHANGELOG.md
activeSupportColumn: false
releaseDateColumn: true
command: nomad --version

releases:
  - releaseCycle: "1.2"
    eol: false
    release: 2021-11-15
    latest: "1.2.2"
  - releaseCycle: "1.1"
    eol: false
    release: 2021-05-18
    latest: "1.1.8"
  - releaseCycle: "1.0"
    eol: false
    release: 2020-12-08
    latest: "1.0.14"
  - releaseCycle: "0.12"
    eol: true
    release: 2020-07-09
    latest: "0.12.12"
---
> [Hashicorp Nomad](https://www.nomadproject.io/) is a simple and flexible workload orchestrator to deploy and manage containers and non-containerized applications across on-prem and clouds at scale.

Generally Available (GA) releases of active products are supported for up to two (2) years. Eligible code-fixes and hot-fixes are provided via a new minor release (Z) on top of the latest "major release" branch, for up to two (2) releases from the most current major release. 

A major release is identified by a change in the first (X) or second (Y) digit in the following versioning nomenclature: `Version X.Y.Z.`

Hashicorp uses the same support period and EoL Policy for all its products.

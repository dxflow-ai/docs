---
title: dxflow Engine
description: A self-contained engine for running containerized workflows on Docker, Podman, Singularity, and Apptainer, with a unified CLI, REST API, and web UI
---

dxflow is a self-contained engine that turns any machine into a node for running containerized workflows. Install one binary, and you get a unified CLI, REST API, and web console for orchestrating workflows across Docker, Podman, Singularity, and Apptainer.

## What you get

- **Multi-runtime**: run containers on Docker, Podman, Singularity, or Apptainer
- **Compose workflows**: orchestrate multi-container apps from YAML definitions
- **Three interfaces**: CLI, REST API, and a web console — all backed by the same engine
- **Secure by default**: RSA key-pair authentication with per-key, composable permissions
- **No lock-in**: runs on your existing infrastructure — cloud, on-premise, or laptop

## Start here

::card-group
  ::card{title="Getting Started" to="/docs/getting-started"}
  Install dxflow and run your first workflow
  ::

  ::card{title="User Interface" to="/docs/interface"}
  Manage workflows, files, and shells from the web console
  ::

  ::card{title="CLI Reference" to="/docs/cli"}
  Every command, flag, and option
  ::

  ::card{title="API Documentation" to="/docs/api"}
  Integrate via the REST API
  ::
::

## About

dxflow started at [DiPhyX](https://www.diphyx.com) to replace the sprawl of ad-hoc scripts, clusters, and logs that slow down scientific computing. It grew through real bioinformatics, CFD, and materials-science projects into a production engine that works with GROMACS, Ansys Fluent, custom solvers, and any containerized application.

**Contact**: [dxflow.ai](https://dxflow.ai) · [info@dxflow.ai](mailto:info@dxflow.ai) · [Book a call](https://calendly.com/diphyx/30min)

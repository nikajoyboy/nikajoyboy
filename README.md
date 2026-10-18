# Susano OS

Security-first operating system and tooling platform for research, automation, and hardened deployments.

> Private project draft — not yet public.

## Overview

Susano OS is a modular, security-focused operating system designed for research, automation, and resilient infrastructure workflows. It combines a hardened base, developer-friendly tooling, and a structured automation layer for environments where security, reproducibility, and system control matter.

## What I’m building

- Hardened system foundation for secure environments
- Modular architecture for custom deployments
- Tooling for automation, debugging, and research workflows
- Clean support for virtualization and bare-metal testing
- Reproducible build pipeline for internal release validation

## Core focus

- Security-first system design
- Hardened defaults and reduced attack surface
- Automation and tooling for secure operations
- Research-friendly development environment
- Secure deployment patterns for modern infrastructure

## Architecture

- Boot & kernel layer
- Base userspace and system services
- Security and hardening layer
- Package and service modules
- Tooling and sandbox layer
- Build and release validation pipeline

## Build & development

```bash
git clone https://github.com/nikajoyboy/Susano.git
cd Susano
make setup
make build
```

## Running locally

```bash
./scripts/run-qemu.sh out/dev/susano-dev.img
```

## Current direction

- Secure foundational OS design
- Reproducible internal build flow
- Modular package architecture
- CI-driven validation
- Private release preparation before public publication

## Security mindset

Susano is built with a strong security-first philosophy: minimal default exposure, clean privilege boundaries, secure defaults, reproducible builds, and deliberate configuration discipline.

## Contact

- GitHub: https://github.com/nikajoyboy
- Project: Susano OS
- Maintainer: Nika

---

A system designed for security, control, and deliberate engineering.

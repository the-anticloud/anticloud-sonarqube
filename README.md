# SONARQUBE

> Anticloud offline package — upstream: SonarSource/sonarqube @ `master`.

## What This Project Does

Continuous Inspection

**Topics:** code-quality, sonarqube, static-analysis

## Upstream README

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://assets-eu-01.kc-usercontent.com/ef593040-b591-0198-9506-ed88b30bc023/a23fc7ba-23f0-489a-829d-ed88c0748521/Sonar_Logo_Dark%20Backgrounds.svg">
    <img src="https://assets-eu-01.kc-usercontent.com/ef593040-b591-0198-9506-ed88b30bc023/82c13eba-d95c-4bb8-8007-7ce77c14e043/Sonar_Logo_Light%20Backgrounds.svg" alt="Sonar logo" width="400">
  </picture>
</p>

[![Build](https://github.com/SonarSource/sonarqube/actions/workflows/build.yml/badge.svg)](https://github.com/SonarSource/sonarqube/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=sonarqube&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=sonarqube)
[![AI Code Assurance](https://next.sonarqube.com/sonarqube/api/project_badges/ai_code_assurance?project=org.sonarsource.sonarqube%3Asonarqube-private&token=sqb_c0e2fa9ac4ef89f9a8403c6ba235e108ceb1dce1)](https://next.sonarqube.com/sonarqube/dashboard?id=sonarqube)
[![Release](https://img.shields.io/github/v/release/SonarSource/sonarqube)](https://github.com/SonarSource/sonarqube/releases)
[![Docker pulls](https://img.shields.io/docker/pulls/library/sonarqube)](https://hub.docker.com/_/sonarqube)
[![License](https://img.shields.io/badge/license-LGPL%20v3-blue)](#license)
[![Community](https://img.shields.io/badge/community-forum-blue)](https://community.sonarsource.com/c/sq/10)

<!-- sonar-marketing:start -->
<!-- Marketing maintains this section. For wording changes, consult the relevant Product Marketing Manager (PMM). Repository CODEOWNERS review accuracy and merge changes. -->

# SonarQube

SonarQube is the algorithmic verification platform for code quality and security. Its static analysis applies techniques such as symbolic execution and data and control flow analysis to inspect your code, find bugs, vulnerabilities, and structural problems, and tell you exactly what to fix and why, in your IDE, your pull requests, and your CI pipeline.

This repository holds the source of the **SonarQube Community Build**, the free, open-source edition of the SonarQube platform. It shares the same analysis used across the SonarQube product line.

## Built for the AI era

AI writes code faster than teams can review it, creating verification debt: code reaching production before anyone has confirmed what it does. SonarQube applies the same consistent, explainable analysis to every line, whether a developer or an agent wrote it. Vibe, then verify: generate fast, then verify what reaches production. It is the verification stage of the Agent Centric Development Cycle, running in the outer CI verification loop to verify code before it merges.

## What SonarQube finds

- **Bugs and reliability issues** that break behavior at runtime.
- **Security vulnerabilities and security hotspots**, with clear guidance on the risk and the fix.
- **Maintainability and structural issues** that make code harder to cha

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.

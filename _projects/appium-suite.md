---
title: "Cross-Platform Mobile Automation Suite"
category: "QA Automation"
description: "Enterprise-grade cross-platform mobile UI automation framework built at TrackTik using Appium (Java), UIAutomatorViewer, and CI/CD integration with Travis CI and Jenkins."
stack:
  - Java
  - Appium
  - UIAutomatorViewer
  - Postman
  - Travis CI
  - Jenkins
  - Page Object Model
order: 4
github: "https://github.com/maxwellqiu"
---

## Overview

Built at **TrackTik**, this framework automated cross-platform mobile UI testing across Android and iOS, integrated directly into CI/CD pipelines to catch regressions on every commit.

## Architecture

```
src/
├── pages/               # Page Object classes (Android + iOS)
│   ├── LoginPage.java
│   ├── DashboardPage.java
│   └── ...
├── tests/               # TestNG / JUnit test suites
│   ├── LoginTests.java
│   └── ...
├── utils/               # Driver factory, capabilities config
│   ├── DriverFactory.java
│   └── CapabilitiesConfig.java
└── ci/
    └── .travis.yml      # CI pipeline config
```

## Key Features

- **Page Object Model** in Java — clean separation of locators and test logic, enabling granular fault isolation across mobile platforms
- **API validation** with Postman — verified JSON response accuracy, latency, data integrity, and error rates
- **CI/CD integration** — structured data logging into Travis CI and Jenkins pipelines for every build
- **Training delivery** — delivered internal Appium (Java) training for manual QA staff, reducing manual testing dependency

## Impact

Improved test coverage across mobile platforms and enabled the team to ship with confidence on both Android and iOS, with automated regression signals on every merge.

# Awesome-Visual-Regression-Testing

# Top Visual Regression Testing

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Visual Regression Testing, Visual QA, Screenshot Comparison, UI Testing, Component Testing & Cross-Browser Visual Validation*  
**Last updated: August 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Visual Regression Testing**. These tools help engineering, QA, and frontend teams automatically detect unintended changes in websites, web applications, design systems, components, and responsive layouts.

**Examples** include Applitools, Percy (BrowserStack), Argos, Cypress Cloud Visual Reviews, Chromatic, Loki, Lost Pixel, BackstopJS, SmartBear VisualTest, and Happo.

**Open-source emphasis**: This section is heavily expanded with open-source visual-regression frameworks, screenshot-diffing libraries, browser automation tools, Storybook testing tools, image-comparison engines, and self-hostable visual-testing platforms.

> **Important:** Not every project in the Open-Source section is a complete hosted-platform replacement. Some are lower-level screenshot/diffing libraries or browser automation frameworks that can be assembled into a complete visual-regression pipeline.

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Applitools](https://applitools.com/)**  
  Enterprise visual-testing platform centered around Visual AI, visual regression testing, cross-browser validation, component testing, and automated identification of meaningful UI differences. :contentReference[oaicite:0]{index=0}

- **[Percy](https://percy.io/)**  
  BrowserStack's visual-testing platform for capturing UI snapshots, rendering them across supported environments and responsive widths, comparing them with baselines, and reviewing visual changes through CI/CD workflows. :contentReference[oaicite:1]{index=1}

- **[Argos](https://argos-ci.com/)**  
  Visual-regression testing platform designed around screenshot capture, image comparison, CI integration, pull-request workflows, and collaborative approval of visual changes. Argos also maintains open-source components. :contentReference[oaicite:2]{index=2}

- **[Cypress Cloud Visual Reviews](https://www.cypress.io/)**  
  Cypress ecosystem integrations can be combined with visual-testing services to capture screenshots during Cypress tests and review visual changes alongside automated test workflows. :contentReference[oaicite:3]{index=3}

- **[Chromatic](https://www.chromatic.com/)**  
  Visual testing and review platform closely integrated with Storybook for capturing UI components, detecting visual changes, and reviewing component changes in CI and pull requests. :contentReference[oaicite:4]{index=4}

- **[Loki](https://loki.js.org/)**  
  Visual regression testing solution focused on Storybook components, using automated screenshots and image comparison to detect UI changes.

- **[Lost Pixel](https://lost-pixel.com/)**  
  Visual-regression platform supporting Storybook, Ladle, Histoire, application pages, and custom screenshots. Its core engine is open source, while its hosted platform provides collaboration and review workflows. :contentReference[oaicite:5]{index=5}

- **[BackstopJS Cloud](https://garris.github.io/BackstopJS/)**  
  Hosted offerings and integrations around BackstopJS-style screenshot comparison workflows. BackstopJS itself is open source and can also be completely self-hosted. :contentReference[oaicite:6]{index=6}

- **[SmartBear VisualTest](https://smartbear.com/visualtest/)**  
  Visual-regression testing platform supporting full-page and element-level screenshots, browser/device validation, automated comparisons, and review workflows. :contentReference[oaicite:7]{index=7}

- **[Happo](https://happo.io/)**  
  Visual testing platform supporting component and full-page screenshots, multiple browsers and screen sizes, and integrations with modern frontend testing workflows. :contentReference[oaicite:8]{index=8}

- **[Sauce Labs Visual](https://saucelabs.com/)**  
  Visual-testing capabilities integrated into Sauce Labs' broader browser and application testing platform, including screenshot baselines and visual comparisons. :contentReference[oaicite:9]{index=9}

- **[LambdaTest SmartUI](https://www.lambdatest.com/smartui)**  
  Cloud-based visual-testing platform supporting screenshot capture, visual comparisons, cross-browser/device testing, and integrations with automated testing frameworks. :contentReference[oaicite:10]{index=10}

- **[Wopee.io](https://wopee.io/)**  
  Visual-validation platform that integrates visual checks into automated testing workflows, including Cypress-based testing. :contentReference[oaicite:11]{index=11}

- **[Percy for Storybook](https://percy.io/)**  
  Visual testing workflow for Storybook component libraries, allowing teams to detect unintended changes across UI states and responsive configurations. :contentReference[oaicite:12]{index=12}

- **[Applitools Eyes](https://applitools.com/)**  
  Visual AI testing engine designed to identify meaningful visual changes rather than relying solely on strict pixel-by-pixel comparison. :contentReference[oaicite:13]{index=13}

## Open-Source GitHub Projects

- **[BackstopJS](https://github.com/garris/BackstopJS)**  
  One of the most established open-source visual-regression testing tools. It automatically captures screenshots and compares them against approved reference images, with an interactive visual-diff report and CI support. It supports Chrome Headless and can use Playwright/Puppeteer workflows. :contentReference[oaicite:14]{index=14}

- **[Playwright](https://github.com/microsoft/playwright)**  
  Open-source browser automation framework with built-in screenshot comparison through `toHaveScreenshot()`. It is one of the simplest ways to add visual regression testing directly to end-to-end tests. :contentReference[oaicite:15]{index=15}

- **[Loki](https://github.com/oblador/loki)**  
  Open-source visual-regression testing tool designed primarily for Storybook. It captures component screenshots and compares them against reference images.

- **[Lost Pixel](https://github.com/lost-pixel/lost-pixel)**  
  Open-source visual-regression engine supporting Storybook, Ladle, Histoire, application pages, and custom screenshots. It can run visual tests in CI and serves as an open-source alternative to commercial platforms such as Percy, Chromatic, and Applitools. :contentReference[oaicite:16]{index=16}

- **[reg-suit](https://github.com/reg-viz/reg-suit)**  
  Open-source visual-regression testing toolkit that separates screenshot capture from image comparison and supports cloud/object-storage-backed baseline workflows. It is particularly useful for custom CI pipelines. :contentReference[oaicite:17]{index=17}

- **[jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot)**  
  Jest matcher for image comparisons, enabling screenshot-based visual regression tests directly within Jest test suites. :contentReference[oaicite:18]{index=18}

- **[pixelmatch](https://github.com/mapbox/pixelmatch)**  
  Lightweight image-comparison library that detects pixel-level differences between images. It is frequently used as a building block for custom visual-regression systems.

- **[odiff](https://github.com/dmtrKovalenko/odiff)**  
  High-performance image-diffing utility designed for automated visual testing and screenshot comparison.

- **[Resemble.js](https://github.com/rsmbl/Resemble.js)**  
  JavaScript image-analysis and comparison library useful for building custom screenshot-diff and visual-regression workflows.

- **[LooksSame](https://github.com/garris/looks-same)**  
  Image-comparison library designed specifically around visual testing and screenshot comparison.

- **[Needle](https://github.com/python-needle/needle)**  
  Python-based visual regression testing tool that uses Selenium to capture screenshots and compare them against reference images.

- **[Nightwatch](https://github.com/nightwatchjs/nightwatch)**  
  Open-source browser automation framework that can be used to construct end-to-end and visual-regression workflows.

- **[Cypress](https://github.com/cypress-io/cypress)**  
  Open-source end-to-end testing framework that can capture screenshots and can be paired with image-diff libraries and visual-testing plugins to build self-hosted visual regression pipelines.

- **[Puppeteer](https://github.com/puppeteer/puppeteer)**  
  Open-source browser automation library that can generate deterministic screenshots for custom visual-regression pipelines.

- **[Selenium](https://github.com/SeleniumHQ/selenium)**  
  Open-source browser automation ecosystem that can be combined with screenshot comparison libraries to create custom visual-testing systems.

- **[WebdriverIO](https://github.com/webdriverio/webdriverio)**  
  Open-source browser automation framework with an ecosystem of screenshot and visual-regression integrations.

- **[Storybook](https://github.com/storybookjs/storybook)**  
  Open-source component-development environment that provides an excellent foundation for component-level visual regression testing when combined with Loki, Chromatic, Lost Pixel, or screenshot-diff tooling.

- **[Storybook Test](https://github.com/storybookjs/storybook)**  
  Storybook's testing ecosystem can execute component tests and interact with rendered stories, providing a foundation for automated UI validation.

- **[Vitest](https://github.com/vitest-dev/vitest)**  
  Open-source JavaScript/TypeScript testing framework that can be combined with image-snapshot tooling for component and visual regression tests.

- **[Jest](https://github.com/jestjs/jest)**  
  Open-source JavaScript testing framework with snapshot-testing capabilities and integrations such as `jest-image-snapshot` for image-based visual testing.

- **[Visual Regression Tracker](https://github.com/Visual-Regression-Tracker/Visual-Regression-Tracker)**  
  Open-source visual-regression testing platform designed around screenshot comparison, baseline management, test results, and CI workflows.

- **[Galen Framework](https://github.com/galenframework/galen)**  
  Open-source testing framework focused on validating web layouts and responsive interfaces using declarative specifications.

- **[Needle](https://github.com/python-needle/needle)**  
  Python visual-testing framework for comparing screenshots captured from browser-based tests.

- **[BackstopJS Examples](https://github.com/garris/BackstopJS)**  
  BackstopJS provides a complete reference-based screenshot workflow including capture, comparison, reporting, and approval of changed screenshots. :contentReference[oaicite:19]{index=19}

- **[reg-viz](https://github.com/reg-viz)**  
  Open-source ecosystem for visual regression testing, including screenshot capture, image comparison, and reporting components.

- **[jest-puppeteer](https://github.com/argos-ci/jest-puppeteer)**  
  Browser-testing integration that can be used as part of screenshot-based regression pipelines.

- **[Percy CLI-compatible Workflows](https://github.com/percy)**  
  Percy has open-source client integrations and SDKs that demonstrate how visual snapshots can be captured from test frameworks and submitted for visual review.

### Additional Strong Open-Source Options

- **[BackstopJS](https://github.com/garris/BackstopJS)** — full-featured screenshot-based visual regression testing.
- **[Playwright](https://github.com/microsoft/playwright)** — browser automation with native screenshot assertions.
- **[Loki](https://github.com/oblador/loki)** — Storybook-focused component visual regression.
- **[Lost Pixel](https://github.com/lost-pixel/lost-pixel)** — open-source visual regression engine for Storybook, Ladle, Histoire, pages, and custom screenshots. :contentReference[oaicite:20]{index=20}
- **[reg-suit](https://github.com/reg-viz/reg-suit)** — extensible visual-regression pipeline with external baseline storage.
- **[Visual Regression Tracker](https://github.com/Visual-Regression-Tracker/Visual-Regression-Tracker)** — self-hostable visual-regression platform.
- **[jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot)** — Jest-based image assertions.
- **[pixelmatch](https://github.com/mapbox/pixelmatch)** — lightweight pixel-level image comparison.
- **[odiff](https://github.com/dmtrKovalenko/odiff)** — high-performance image comparison.
- **[Resemble.js](https://github.com/rsmbl/Resemble.js)** — JavaScript image comparison.
- **[LooksSame](https://github.com/garris/looks-same)** — image comparison optimized for visual testing.
- **[Galen Framework](https://github.com/galenframework/galen)** — responsive layout and visual validation.
- **[Needle](https://github.com/python-needle/needle)** — Selenium/Python visual regression.
- **[Cypress](https://github.com/cypress-io/cypress)** — browser testing foundation for custom visual-regression systems.
- **[Puppeteer](https://github.com/puppeteer/puppeteer)** — programmable screenshot capture.
- **[Selenium](https://github.com/SeleniumHQ/selenium)** — browser automation foundation.
- **[Storybook](https://github.com/storybookjs/storybook)** — component-driven foundation for visual testing.
- **[Jest](https://github.com/jestjs/jest)** — test framework supporting snapshot-based workflows.

**A practical open-source stack** can look like:

`Storybook → Playwright/Loki/Lost Pixel → Screenshot → pixelmatch/odiff → Baseline → CI → PR Review`

For full-page web applications:

`Playwright/Puppeteer → Screenshot → pixelmatch/odiff → HTML Diff Report → CI/CD`

For a more complete self-hosted platform:

`Browser Automation → Screenshot Capture → Image Diff Engine → Baseline Storage → Visual Diff UI → PR Integration`

For component libraries:

`Storybook → Loki/Lost Pixel → Browser Rendering → Screenshot Comparison → Baseline Approval`

### Visual Regression Testing Architecture

A typical visual-regression workflow consists of:

1. **Render** the application or component.
2. **Capture** screenshots at defined browsers, viewports, and states.
3. **Compare** the new screenshot against an approved baseline.
4. **Calculate** the visual difference.
5. **Filter** insignificant rendering noise using thresholds or masking.
6. **Review** the visual diff.
7. **Approve** intentional changes.
8. **Fail CI** when unexpected visual changes exceed the configured threshold.

The core pipeline can be represented as:

`Application → Browser → Screenshot → Image Diff → Baseline → Visual Report → Human Approval`

### Open-Source vs SaaS

| Capability | Open Source | SaaS / Hosted |
|---|---:|---:|
| Screenshot comparison | ✅ | ✅ |
| Baseline management | ✅ | ✅ |
| CI/CD integration | ✅ | ✅ |
| Self-hosting | ✅ | Usually ❌ |
| Custom infrastructure | ✅ | Limited |
| PR workflows | Usually configurable | Usually built-in |
| Collaboration UI | Varies | Usually strong |
| Cross-browser infrastructure | DIY | Usually built-in |
| Visual AI | Rare | Common in enterprise platforms |
| Large-scale parallel rendering | DIY | Usually built-in |
| Data control | High | Vendor-dependent |
| Operational overhead | Higher | Lower |
| Cost | Infrastructure cost | Subscription/usage cost |

The biggest distinction is that open-source tools generally give teams control over **browser execution, screenshots, baselines, and comparison algorithms**, while SaaS platforms commonly add managed rendering infrastructure, collaboration, visual-review workflows, cross-browser execution, analytics, and enterprise-scale management.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Open-source projects differ significantly in scope: some are complete visual-regression platforms, while others are screenshot tools, browser automation frameworks, image-diff engines, component-testing frameworks, or layout-validation libraries.
- Pixel-level comparison can generate false positives from anti-aliasing, fonts, browser versions, operating-system rendering, animations, timestamps, dynamic content, and other environmental differences.
- For reliable results, teams should standardize browser versions, fonts, viewport dimensions, test data, animations, and rendering environments.
- Visual regression testing should complement functional, accessibility, performance, and end-to-end testing rather than replace them.

---

**Made for frontend engineers, QA engineers, designers, DevOps teams, design-system maintainers, and software-testing teams.**  
Let's make visual regression testing more open, automated, reproducible, and accessible.

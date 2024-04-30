# End-to-End Testing Framework

[![](https://img.shields.io/badge/Discussion-6-green)](https://github.com/registry-operator/adr/issues/6)

## Context and Problem Statement

Ensuring the reliability and functionality of the registry-operator is essential to maintain a seamless experience for developers and DevOps teams utilizing CNCF Distribution Registry instances. End-to-end testing plays a critical role in validating the deployment, scaling, and management capabilities of the registry-operator across various scenarios.

The selection of an appropriate end-to-end testing framework is paramount to establish robust testing standards and practices. Factors such as adherence to language idioms, support for testing complex workflows, community adoption, and extensibility are crucial considerations in this decision-making process.

## Considered Options


* [behave](https://github.com/behave/behave) (Python)
* [Kyverno Chainsaw](https://kyverno.github.io/chainsaw/latest/) (low-code, YAML)
* [Ginkgo](https://onsi.github.io/ginkgo/) and [Gomega](https://onsi.github.io/gomega/) (Go)
* [pytest-bdd](https://github.com/pytest-dev/pytest-bdd) (Python)
* [Radish](https://github.com/radish-bdd/radish) (Python)
* [testing](https://pkg.go.dev/testing) (Go)

## Decision Outcome

Selected option: *Kyverno Chainsaw*, because it extremly simple to build tests, tests are executed really quickly, community is quickly growing.

## Previous Selections

~~Selected option: *pytest-bdd*, because it has great community support, integrates well with other *pytest* plugins, is well integrated with `*.feature` files.~~

## Changelog

| Date       | Description                                               |
|------------|-----------------------------------------------------------|
| 2024-04-30 | changed decision from *pytest-bdd* to *Kyverno Chainsaw*. |

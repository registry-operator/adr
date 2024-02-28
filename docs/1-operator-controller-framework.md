# Operator/Controller framework

[![](https://img.shields.io/badge/Discussion-1-green)](https://github.com/registry-operator/adr/issues/1)


## Context and Problem Statement

The registry-operator should be a critical component in managing CNCF Distribution Registry instances efficiently. However, selecting the appropriate base operator/controller framework is pivotal for ensuring the scalability, maintainability, and extensibility of the registry-operator.

Considerations:
- the framework must provide robust functionality to streamline deployment, scaling, and management of container image registries, aligning with the objectives of the `registry-operator`;
- it should offer ease of development and maintenance, allowing the maintainers to efficiently manage and extend the operator's capabilities as per evolving requirements;
- community support, documentation quality, and integration capabilities with other Kubernetes ecosystem components are crucial factors to weigh in our decision-making process.

## Considered Options

* [Kubebuilder](https://book.kubebuilder.io/)
* [Operator-SDK](https://sdk.operatorframework.io/docs/building-operators/golang/)
* [Kube.rs](https://kube.rs/controllers/intro/)

## Decision Outcome

Selected option: *Operator-SDK*, because it is based on Kubebuilder with additional features, without introducing much additional complexity to the project.

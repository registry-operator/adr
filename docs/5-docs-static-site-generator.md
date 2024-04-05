# Static Site Generator for Documentation

[![](https://img.shields.io/badge/Discussion-5-green)](https://github.com/registry-operator/adr/issues/5)

## Context and Problem Statement

Effective documentation is paramount for the successful adoption and utilisation of the `registry-operator`, a robust tool tailored for managing CNCF Distribution Registry instances. As developers and DevOps teams engage with the `registry-operator`, they require comprehensive, easily accessible documentation to streamline deployment, scaling, and management tasks.

The choice of documentation framework or static site generator is crucial to ensure that the documentation meets the needs of our users. Templating flexibility, support for custom scripts, and availability of extra plugins for enhancing functionality are key factors to consider in this decision-making process.

## Considered Options

* [MKDocs](https://www.mkdocs.org) + [Material Theme for MKDocs](https://squidfunk.github.io/mkdocs-material/);
* [Hugo](http://gohugo.io) + [Docsy Theme](https://www.docsy.dev);
* [Hugo](http://gohugo.io) + [Doks Theme](https://github.com/gethyas/doks);
* [Docusaurus](https://docusaurus.io);
* [Cobalt](http://cobalt-org.github.io);
* [Zola](https://www.getzola.org).

## Decision Outcome

Selected option: _MKDocs + Material Theme for MKDocs, because:
- Great documentation of the tool;
- Versioning support out-of-the-box with static versioning via Mike;
- Lots of customization options;
- Sane defaults;

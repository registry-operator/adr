# Static Site Generator for Documentation

[![](https://img.shields.io/badge/Discussion-5-green)](https://github.com/registry-operator/adr/issues/5)

## Context and Problem Statement

[Describe the context and problem statement prompting the need for this mADR.]

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

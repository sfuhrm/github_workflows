 github_workflows
============
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This is a repository of reusable github workflows.
Please see [reusing-workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows)
for the basics.

Overview
---

* `maven.yml`: Build a Java artifact.
* `jacoco-badge.yml`: Calculate a Jacoco coverage badge icon and store it in the repository.
* `maven-expression.yml`: Calculate a Maven expression (i.e. a variable expansion for `project.version`) and store it as an usable output.
* `maven-deploy-snapshot-sonatype-oss.yml`: Build and deploy a snapshot to Sonatype OSS.

Status
---

The repository is experimental at the moment. I do not recommend using workflows without sticking to a specific git revision.

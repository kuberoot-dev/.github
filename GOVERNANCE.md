# Governance

This document describes how the kuberoot project — the repositories of the [kuberoot-dev](https://github.com/kuberoot-dev) organization — is run today, and how that is meant to change as people join.

## Today: one maintainer

kuberoot was started by Timur Tukaev ([@tym83](https://github.com/tym83)) and, for now, has a single maintainer, who manages the project and makes its decisions: what is in scope, which changes are merged, when releases are cut, and who else becomes a maintainer.

This is a statement of where the project is, not of where it should stay. Sharing responsibility with the people who build the project is the goal; it happens as contributors show sustained work, as described below.

## How decisions are made

- Decisions are made in the open, on GitHub: in issues, pull requests and discussions. A decision that is not written down there has not been made.
- Anyone may propose a change, a new distribution, a package or a change of direction by opening an issue or a pull request.
- Pull requests from contributors are merged after a maintainer approves them and continuous integration passes.
- When the maintainer declines a proposal, the reason is given in the issue or pull request.

## Roles

**Contributors** are everyone who opens issues, reviews, writes code, documentation or package recipes, tests on hardware, or helps others. No permission is needed to become one.

**Reviewers** are contributors trusted to review pull requests in an area (a repository, a distribution, a set of package recipes). Their review is weighed in the decision to merge.

**Maintainers** may merge pull requests and cut releases in the repositories they maintain, and take part in decisions about the project. Maintainers are listed in [MAINTAINERS.md](MAINTAINERS.md).

## Becoming a reviewer or a maintainer

Responsibility follows sustained contribution. There is no fixed formula, but what the maintainers look for is:

- contributions over a period of several months, not a single burst;
- non-trivial changes merged in the area, and reviews of other people's changes there;
- an understanding of the project's design and its conventions, and care for the users of the area;
- conduct in line with the [Code of Conduct](CODE_OF_CONDUCT.md).

A contributor may ask to become a reviewer or a maintainer, or be nominated by an existing maintainer. Becoming a maintainer is decided by the maintainers and recorded in MAINTAINERS.md through a pull request.

## As the project grows

Once there are three or more maintainers, decisions move from the founder to the maintainers as a group: by lazy consensus in the open, and, where consensus is not reached, by a simple majority vote of the maintainers. This document will then be revised to describe that process in detail.

## Stepping down

A maintainer may step down at any time by opening a pull request against MAINTAINERS.md. A maintainer who has been inactive for a long time may be moved to emeritus status by the other maintainers, with thanks.

## Changes to this document

Changes to this governance are made by pull request and decided by the maintainers.

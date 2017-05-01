---
title: Contribution guidelines for my projects
---

# Contribution guidelines

These are contributing guidelines for my projects hosted on GitHub.

## Direct code contributions

My repositories accept direct code contributions in the form of issue-less pull requests.

These contributions should be done through forking the repository and creating pull requests
towards the main repository.

## Preferred contribution procedure

Preferred contribution procedure is to take an up-for-grabs issue from GitHub, create a fork of
the code, and create a pull request with the changes. Please refer to each individual project
for links to their up-for-grabs iussues.

## Acceptance Guidelines

Contribution will be accepted if:

- They make sense (or, if their sense is not immediately noticeable, are explained through
comments)
- They don't break the build or unit tests
- They are not changing the style and formatting of the code (especially pull requests that
focus exclusively on such changes)
- They pass the standards set by the StyleCop analyzer
- They introduce an actual useable feature, or new unit tests
- They don't introduced other dependencies, unless they are discussed first
- They don't mess around with build/project/tool settings

Necessary compatibility:

- The resulting code has to be compatible with Visual Studio 2017; earlier versions don't have
to be supported
- The resulting code must be compatible with the already-selected .NET standard version; if
it is necessary that a new version be added to the list, or the minimal one updated, please
ask first

A few notes about unit test contributions:

- Unit tests use the [xunit.net](https://xunit.github.io/) framework - please do not use anything
but that
- Unit test contributions must not rely on magic numbers, unless it is a specific scenario for a
magic number that you are testing; instead, please use randomness as much as possible

A few notes about bugfixes:

- Please do not submit bugfix pull requests unless you also explain the bug first
- A bug fix should also have a unit test dedicated to it

Also, contributions will be accepted if they highlight and fix typos in any part of the
repository.
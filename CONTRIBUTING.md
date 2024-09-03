# Contributing Guidelines

The following is a set of guidelines for contributing to nginx project.
We really appreciate that you are considering contributing!

## Table of Contents

- [Getting Started](#getting-started)
- [Ask a Question](#ask-a-question)
- [Contributing](#contributing)
  - [Issues and Discussions](#issues-and-discussions)
    - [Open a Discussion](#open-a-discussion)
    - [Report a Bug](#report-a-bug)
    - [Suggest an Enhancement or Request a Feature](#suggest-an-enhancement)
    - [Issue lifecycle](#issue-lifecycle)
  - [Open a pull request](#open-a-pull-request)
- [Git Guidelines](#git-guidelines)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Ask a Question

To ask a question, please open an issue on GitHub with the label `question`.

## Open a Discussion

If you have any questions, ideas, or simply want to engage in a conversation
with the community and maintainers, we encourage you to use
[GitHub Discussions](https://github.com/nginx/nginx/discussions).

## Report a Bug

To report a bug, open an issue on GitHub with the label `bug` using the
available bug report issue template. Before reporting a bug, make sure the
issue has not already been reported.

## Suggest an Enhancement or Request a Feature

To suggest an enhancement or request a feature,
[open an idea](https://github.com/nginx/nginx/discussions/new?category=ideas)
on GitHub discussions.  We highly recommend that you open a discussion about
a potential enhancement or new feature before opening an issue. This enables
the maintainers to gather valuable insights regarding the idea and its use
cases, while also giving the community an opportunity to provide valuable
feedback.

## Pull requests

Follow this plan to contribute a change to NGINX source code:

- Fork the NGINX repository
- Create a branch
- Implement your changes in this branch
- Submit a pull request (PR) when your changes are tested and ready for review

Refer to
[NGINX Development Guide](https://nginx.org/en/docs/dev/development_guide.html)
for questions about NGINX programming.

### Formatting changes

- Changes should be formatted according to the
[code style](https://nginx.org/en/docs/dev/development_guide.html#code_style)
used by NGINX; sometimes, there is no clear rule, in which case examine how
existing NGINX sources are formatted and mimic this style; changes will more
likely be accepted if style corresponds to the surrounding code

- Keep a clean, concise and meaningful commit history on your branch, rebasing
locally and breaking changes logically into commits before submitting a PR

- Each commit message should have a single-line subject line followed by verbose
description after an empty line

- Limit the subject line to 67 characters, and the rest of the commit message
to 76 characters

- Reference issues in the the subject line; if the commit fixes an issue,
[name it](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)
accordingly

### Before submitting

- The proposed changes should work properly on a wide range of
[supported platforms](https://nginx.org/en/index.html#tested_os_and_platforms)

- Try to make it clear why the suggested change is needed, and provide a use
case, if possible

- Passing your changes through the test suite is a good way to ensure that they
do not cause a regression; the repository with tests can be cloned with the
following command:

```bash
git clone https://github.com/nginx/nginx-tests.git
```

- Submitting a change implies granting project a permission to use it under the
[BSD-2-Clause license](https://github.com/nginx/nginx/blob/master/LICENSE)

## Issue lifecycle

To ensure a balance between work carried out by the NGINX engineering team
while encouraging community involvement on this project, we use the following
issue lifecycle:

- A new issue is created by a community member

- An owner on the NGINX engineering team is assigned to the issue; this
owner shepherds the issue through the subsequent stages in the issue lifecycle

- The owner assigns one or more
[labels](https://github.com/nginx/nginx/issues/labels) to the issue

- The owner, in collaboration with the wider team (product management and
engineering), determines what milestone to attach to an issue.
Generally, milestones correspond to product releases.

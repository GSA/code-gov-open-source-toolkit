# Source Code Automation

## What is source code automation?

## How is it beneficial to developers?

### What could be automated
* Set up automatic tests that will run on all incoming contributions, and ensure that your tests can be easily be run locally by contributors.
* Require that all code contributions pass your tests before they can be submitted (required status checks).
* If tests are added, make sure to explain how they work in the Contributing file. Don’t make standards too complicated or that they increase barriers to contribution – should relieve developers of repetitive, low brain power work.
* Include automatic tests that can be run locally by developers pre-commit to check for non-public information that is inappropriate for contribution (e.g., tools like [cfpb's clouseau](https://github.com/cfpb/clouseau) or [git secrets](https://github.com/awslabs/git-secrets)).

### Maintenance work
* [Semantic-release](https://github.com/semantic-release/semantic-release) automates releases
* [mention-bot](https://github.com/facebook/mention-bot) mentions potential reviewers for pull requests
* [Danger](https://github.com/danger/danger) helps automate code review
* [Issue templates and pull request templates](https://github.com/blog/2111-issue-and-pull-request-templates)
* Style guides
* Linters

### Resources
* GitHub’s Open Source Guide [Best Practices for Maintainers](https://opensource.guide/best-practices/)
* [Required status checks](https://help.github.com/en/articles/about-required-status-checks)
* GitHub’s [Tools for Open Source](https://github.com/collections/tools-for-open-source) – software to make running an open source project a little easier
* GitHub’s [issue templates and pull request templates](https://github.com/blog/2111-issue-and-pull-request-templates)
* [Semantic-release](https://github.com/semantic-release/semantic-release) automates releases
* [Kubernetes Development Automation](https://github.com/kubernetes/community/blob/master/contributors/devel/automation.md) documentation
* [Microsoft's CodeQL] (https://securitylab.github.com/tools/codeql) implements a semantic code analysis engine, is github-integrated and is open source

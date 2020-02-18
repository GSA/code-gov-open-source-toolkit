# Community building and maintenance

**Places to Congregate**
It’s important to give your community a place to congregate to help them get to know each other. When communication is public and accessible, anyone can read past archives and get up to speed and participate. 

Secondly, as a maintainer, if you don’t give people a public place to talk about your project, they will likely contact you directly. Public communication can be as simple as directing people to open an issue instead of emailing you directly or commenting on your blog.

Ideas for building community:

* Live chat (e.g., Slack channels, IRC, or Gitter)
* Forum/thread-based communities (e.g., Discourse)
* In-person meetups, conferences or events
* GitHub issues or listserv
* Office Hours
* Social Media

Notable exceptions to public communication are: 1) security issues and 2) sensitive code of conduct violations. People should be able to report these issues privately. 

# Code Review

* All code in any code-base should look like a single person typed it, no matter how many people contributed. Principles of writing idiomatic JavaScript (WP-CLI)
* Code review should probably always be your top priority, and you should figure out the best way to work it into your event loop (pending code review requests represent blocked threads of execution)
* Make your review requests a pleasure to read

**Reviewers**
* Understand what the proposed change does and why it’s essential
* Review for correctness; if it addresses the business and UX requirements, then check for security; then check for readability ; then check for elegance and quality
* Make sure you know what reviews you’re on the hook for (bot can automatically assign)
* Shorten your event loop; when possible, be interrupt-driven
* Prioritize code review above your other work (except for outages and customer service)
* Expect to spend time on code review every day, throughout the day
* Be thorough, each and every time

**Submitters**
* Dot your I’s and J’s (submit something you like that falls within style guidelines)
* Keep reviews as small as possible
  * Write good titles ad descriptions
  * Title should distinguish your review
* Description should tell the story of the change – why you’re making it, what problem you’re solving, what code was changed, what classes were introduced, how it was tested
* Acknowledge comments quickly and learn from suggestions
* Explain yourself if you feel the reviewer seemed to misunderstand your intent

**Submitting a PR**
* Some projects, like Kubernetes, require that contributors sign a CLA as a prerequisite; if that is the case, don’t make this a barrier to contribution
* Search existing issues; if you can’t find anything related to what you want to work on, open a new issue in the appropriate repo so you can get initial feedback
  * Opening an issue before submitting a PR helps us provide architectural and implementation guidance before you spend too much time on the code
* Fork the repository you’d like to modify, either the framework or one of the command packages
* Create a branch for each issue you’d like to address. Commit your changes.
* Push the code changes from your local clone to your fork.
* Open a PR. It doesn’t matter if the code isn’t perfect. The idea is to get reviewed early and iterate on it.
* The smaller the proposed change, the better. If you’d like to propose two unrelated changes, submit two PRs
* The more information, the better. Make use of the PR body to describe what changes were made, why you made them, and what impact they will have for users
* Tests are required
* Coding standards
* Refrain from unnecessary code churn (any code changes should have clear and obvious value)
* Contributions are atomic (each PR should contain one conceptual change)
* Make regular progress on your contribution (e.g., if changes are needed and two weeks pass, the PR is considered abandoned. Someone else may pick it up or it may be closed)
* Once your PR has passed code review, it will be merged into master and be in the pipeline for the next release

**Code Review Workflow example (WP-CLI)**
* Every commit pushed to a GH branch, automated CI tests – linting for all code, unit tests for functional code, and ideally, behavioral and automated acceptance testing – are run on Travis
* If the build passes, the PR can be reviewed. If not, the original developer is responsible for getting the build to the point where it passes
* When the original developer is satisfied with their work, they can request review from the commiters team by assigning @name for review
* Simple PRs can often be merged by the developer who reviews them. More complex changesets will often require conversations back and forth between reviewer and developer, and should have secondary reviewers
* GitHub’s “Files Changed” tab is a good place to leave inline comments on specific parts of the changeset. More general comments can be left on the PRs “Conversation” tab
* The reviewer may suggest changes in the form of a PR off the branch being reviewed, or in comments
* The developer will make changes suggested, discuss the issue for clarity, and may mention the reviewer when they are satisfied with their work
* If a PR needs final cleanup before merging or has been abandoned, the reviewer can commit directly to the branch. However, avoid rewriting code without consultation
* When the reviewer is satisfied with changes, they can either merge or assign the PR to a second reviewer for merge. The original developer (and ideally the reviewer) should both be available for a couple of days post-merge to address any issues that arise

**Timely Code Reviews**
* Some projects (e.g., CFPB) tag certain groups to review (@frontend vs. @backend)
* Ensure contributor has completed associated unit tests and/or functional tests

**Maintainer Feedback**
* Maintainers should say thank you and any feedback should be constructive
  * Help get contribution to a place where you’re comfortable in accepting it
  * Help them learn how to contribute again in the future more effectively
  * Pass on some knowledge to the contributor
* Consider using Contributing.md document (or a separate doc) to outline community membership roles and how contributors can move up the ladder
    
**Resources**
* Open Source Guides guide on [Building Welcoming Communities](https://opensource.guide/building-community/)
* Glen Sanford: [On Code Review](https://glen.nu/ramblings/oncodereview.php)
* [Code Review Workflow](https://make.wordpress.org/cli/handbook/code-review/)
* [Expectations when submitting a PR](https://make.wordpress.org/cli/handbook/pull-requests/#running-and-writing-tests)
* [CFPB Contributing](https://github.com/cfpb/cfgov-refresh/blob/master/CONTRIBUTING.md) – an example of providing internal and external contribution guidance
* [Contribution Feedback](https://snarky.ca/setting-expectations-for-open-source-participation/)
* [Kubernetes Community Membership](https://github.com/kubernetes/community/blob/master/community-membership.md)
* [Kubernetes Community Expectations](https://github.com/kubernetes/community/blob/master/contributors/guide/community-expectations.md)
* [Kubernetes Pull Requests](https://github.com/kubernetes/community/blob/master/contributors/guide/pull-requests.md) documentation
* [WP-CLI Code Review](https://make.wordpress.org/cli/handbook/code-review/) documentation
* [WP-CLI Pull Requests](https://make.wordpress.org/cli/handbook/pull-requests/#running-and-writing-tests) documentation
* [Jekyll Contributing](https://jekyllrb.com/docs/contributing/) documentation with instructions for submitting a PR via github.com and via the Git command line; also differentiates between code and documentation contributions
* [Setting expectations for open source participation](https://snarky.ca/setting-expectations-for-open-source-participation/) blog by Brett Cannon
* [Rust Language community page](https://www.rust-lang.org/community)

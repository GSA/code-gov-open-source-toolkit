# Documentation
According to GitHub’s own Open Source Survey, “documentation is highly valued, frequently overlooked, and a means for establishing inclusive and accessible communities” (2017). The survey found incomplete or outdated documentation is a pervasive problem observed by 93% of their respondents (GitHub, 2017). 
Documentation that clearly explains a project’s processes in accessible, plain language invites people to interact with it and is valued more by groups that are underrepresented in open source, like women and those who didn’t grow up speaking English (Building Welcoming Communities, n.d.).
Documentation tells people why your project exists, how to install it, and how to use it. It also provides a way to discover the history of your code and why certain behaviors have changed since inception. In many respects it is the guide to the maturation of a particular project. 
Writing documentation improves the design of your code. For example, talking through your API and design decisions on paper allows you to think about them in a more formalized way and gives it structure and an easy to read approach. A nice side effect is that it allows people to contribute code that follows your original intentions as well. And, if they do decide to change the functionality, there will be an explanation as to why it was done the way it was. In this repo you will find some of the core elements to practicing good documentation. We hope that you take away with you a better sense of how to document code!
 
Here you will find a Checklist for what documents should be included in a repository as a minimum (see templates below):
* Code of conduct - recommendations
* License - per Ian Lee, agencies default to Creative Commons license because they can’t hold copyright, but it is not an approved OS license (agencies like NASA, DOD have their own licenses for some projects)
* README - makes it easier for anyone who lands on your project to get started
   * New Contributors section (nice-to-have?)
   * Quickstart information
* CONTRIBUTING - clearly explains how to contribute
   * Community Expectations (SLAs) section - or potentially make this a separate document

Nice-to-have
* Contributors/Authors (nice-to-have) - highlights contributors
* VISION
* Project roadmap
* GOVERNANCE
* Communication - explains the various communication methods used by the project and provides some minimal guidance on using them
* GitHub 101 for government
* Troubleshooting guide
* Community Membership - outlines responsibilities of contributor roles and how contributors can move up the ladder (e.g., member, reviewer, approver, subproject owner)

Resource: Standard templates
**Readme**

[Jekyll’s readme](https://github.com/jekyll/jekyll) documentation includes the following sections:
* Badges for gem, Linux build, Windows build, maintainability, test coverage, security, backers, and sponsors
* Philosophy
* Getting Started
* Diving In
* Need Help?
* Code of Conduct?
* Credits with sponsor icons, contributors profile pics, and backers profile pics
* License

**Contributing**
* Welcome and thanks
* Variety of contributions
   * Feature requests
   * Bug reports
   * Pull requests
   * Issue triage/comment on open issues (have you experienced the same problem? Do you know a workaround? Do you have a suggestion for how the feature could be better?)
   * Writing tutorials
   * Giving a demo at your local meetup
   * Helping other users with their support questions
   * Revising/writing documentation (anytime you see something confusing or have a suggestion to improve)
   * Install locally and kick the tires to see if it works and does what you’d expect
Provide helpful links and information

**Troubleshooting Guide examples**
* WP-CLI includes the following sections in their troubleshooting guide:
* How do I get more verbose informations about my WP-CLI installation?
* What should I do before I start debugging issues?
   * What should I do if the WP-CLI output is different than expected?
   * Environment Variables
   * WP-CLI Configuration Files
   * WP-CLI- Packages
   * WordPRess Configuration File
   * WordPress Extensions
* What should I do if WP-CLI reports an error?
* I have checked all above, but still have an issue. Where can I report issues?

**Resources**
* Google’s Open Source docs
* https://opensource.org/licenses - info on licenses 
* https://github.com/rtfd/readthedocs.org/blob/master/AUTHORS.rst - example of an Authors doc
* https://www.writethedocs.org/guide/writing/beginners-guide-to-docs/ - write up of a presentation
* https://developers.google.com/season-of-docs/ - fostering open source collaboration with technical writers
* https://github.com/jekyll/jekyll/blob/master/README.markdown - I like how contributors are highlighted in README
* https://joss.theoj.org/about - Journal of Open Source Software
* [GitHub in Government](https://github.com/jbjonesjr/github-in-government/blob/master/github-training.md) – a markdown file with many helpful links to training, tutorials, videos, onboarding and other documentation (including something you did on version control!)
* [Contributing to Data.gov with GitHub 101](https://github.com/GSA/data.gov/wiki/Contributing-to-Data.gov-with-GitHub-101) – Data.gov’s guidance to their contributors
* [Using GitHub](https://software.llnl.gov/about/using-github/) – LLNL’s guide for getting started with GitHub, specific to LLNL developers working in the LLNL GitHub organization
* [GitHub](https://handbook.18f.gov/github/) – TTS Handbook on setup, rules, how-to, tips and resources
* [WP-CLI Contributing](https://make.wordpress.org/cli/handbook/contributing/) documentation
* [WP-CLI Quickstart](https://make.wordpress.org/cli/handbook/quick-start/) documentation
* [WP-CLI Troubleshooting](https://make.wordpress.org/cli/handbook/troubleshooting/) documentation
* [Rust-lang Contributing](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md) documentation
* [Rust-lang Readme](https://github.com/rust-lang/rust) with quickstart documentation
* [Rust-lang Governance](https://www.rust-lang.org/governance) documentation
* [Jekyll’s Readme](https://github.com/jekyll/jekyll) highlights contributors, sponsors and backers with [quickstart](https://jekyllrb.com/docs/) info
* [Jekyll’s Contributing](https://jekyllrb.com/docs/contributing/) documentation gives examples of types of contributions and expectations for submitting PRs
* [Kubernetes Community Expectations](https://github.com/kubernetes/community/blob/master/contributors/guide/community-expectations.md) documentation
* [Kubernetes Community Membership](https://github.com/kubernetes/community/blob/master/community-membership.md) documentation 
* [Homebrew](https://docs.brew.sh/) documentation
* [CocoaPods Guides and documentation](https://guides.cocoapods.org/)

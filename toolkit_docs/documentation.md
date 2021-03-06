# Documentation
Documentation in software development, like documentation in any industry, is used to articulate and describe the system itself and the parts that make it up. It also makes it possible for those reading code to understand, in plain language, the formulation and decisions that went into developing the code that was written. In many respects it is the "cheat sheet" that developers use when reviewing another person's project. At the same time it is one of the most difficult aspects of software development to master. Truly good coders are also great at documenting. And to create long lasting, functional code one must also do the same with the documenation that is associated with it.

## Why is this tool important?
Documentation tells people why your project exists, how to install it, and how to use it. It also provides a way to discover the history of your code and why certain behaviors have changed since inception. In many respects it is the guide to the maturation of a particular project. According to GitHub’s Open Source Survey in 2017, “documentation is highly valued, frequently overlooked, and a means for establishing inclusive and accessible communities." The survey found incomplete or outdated documentation is a pervasive problem observed by 93% of their respondents. What can also be gleaned from this information is that a lack of documentation could correlate to less re-use of your open source project. Some of the factors could be not knowing how to set up the project, 
Documentation that clearly explains a project’s processes in accessible, plain language invites people to interact with it and is valued more by groups that are underrepresented in open source. 
Writing documentation also improves the design of your code. For example, talking through your API and design decisions on paper allows you to think about them in a more formalized way and gives it structure and an easy to read approach. A nice side effect is that it allows people to contribute code that follows your original intentions as well. And, if they do decide to change the functionality, there will be an explanation as to why it was done the way it was. In this repo you will find some of the core elements to practicing good documentation. We hope that you take away with you a better sense of how to document code!
 
 ## What are some common applications?
 
 In most software development projects, documentation is broken out into two sections. The first is system documentation and the second is process documentation. Both are necessary, but depending on who your audience is you will want to tailor your approach accordingly. One of the most basic applications of documentation is how to set up your project in a given environment. This is especially necessary if you are interested in having others work and contribute to your code. Many hackathons across the country begin by ensuring that the project that is going to be worked on has accurate and up-to-date documenation on how to set up the environment to launching the given application. Proper, step-by-step product documentation will enable for easy set up and installation of your code.

Another common application of documentation, this time more process oriented, is developing the release notes or the testing schedule of your particular project. Code.gov issues release notes (see here) on a regular basis to inform users on what has changed or improved from the previous iteration. This form of documentation is of great use to the community because it demonstrates the new features that may impact their fork of the code and perhaps highlights vulnerabilities that were addressed from a previous issue. At the same time it showcases the livelihood of the project and the members of the team that are working on it. Without release documentation other teams are informed of the life and iterations of a particular project.

## How to begin using it
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

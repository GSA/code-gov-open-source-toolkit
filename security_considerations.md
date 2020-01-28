#Security Considerations
* Treat everything as code, which will ensure that known regulations are followed (and make it easier to ensure patches are universally applied)
* Embrace automation – e.g., Dynamic Application Security Testing solutions, static code analysis to provide automated, early detection of security issues to complement peer reviews
* Bring developers and security together – start with an initial secure coding workshop and include them in design reviews, etc.
  * Developers need to build security skills (not inherent)
* Build a security-first culture
* Coverity Scan provides free deep scans of open source software that include the Common Weakness Enumeration (CWE/SANS) Top 25 vulnerabilities
* If using Docker containers, can take advantage of Docker Security Scanning
* Suggestion to submit a “software bill of materials” or SBoM, which lists the various components that underlie a particular system – so if a bug is discovered, agencies could quickly scan the bill of materials to see if the application contains the compromised code
  * DHS requires vendors to submit SBoMs for every tool offered
  * National Telecommunications and information Administration launched a program to explore how SBoMs could improve software transparency
  * SBoMs won’t guarantee security, but it can improve your knowledge of inventory that’s represented in your software
* Automation, SBoMs, and prioritizing security in every IT purchase (make cyber protections standard in software acquisitions)
  * Government policies on using open source focus on licensing, not security

**Example security policy from Django**
* Outline commitment to reporting and disclosure of security-related issues; policies are geared towards allowing delivery of timely security updates to the official distribution of Django and third-party
* Reporting can be done by emailing (with address provided) which goes to security team; should receive a response within 48 hours
  * Note: normal bugs are reported in their public Trac, but security issues shouldn’t be reported publicly
  * Also, provide option to send an encrypted email with public key ID provided
* Notes the supported versions
  * Master development branch, which is next major release receives security support but if issues only affect this branch and not any stable released versions, then it is fixed in public
  * Two most recent release series receive security support
  * Long-term support releases will receive security updates for a specified time period
* How security issues are disclosed (outlines steps from private discussion to public disclosure)
  * One week before public disclosure, two notifications are sent:
    * First, Django-announce (listserv for upcoming security releases, new releases, and security advisories) is notified of date and approximate time of the upcoming security release, as well as the severity of the issues (to aid organizations that need to ensure they have staff available to handle triaging)
    * Second, a list of people and organizations (operating-system vendors and other distributors) are notified and the email is signed with the PGP key of someone from Django’s release team and includes:
      * A full description of the issue and affected versions
      * Steps to remedy
      * Patch(es), if any, that will be applied
      * Date on which the team will apply patches, issue new releases and publicly disclose the issue
  * Day of disclosure, the following steps are taken:
    * Apply relevant patch(es) to codebase
    * Issue relevant release(s), by placing new packages on the website, and tagging new releases in git repository
    * Post a public entry on official blog, describing the issue and its resolution in detail, pointing to relevant patches and new releases, and crediting the reporter of the issue (if they want to be publicly identified)
    * Post a notice to the Django-announce and oss-security@lists.openwall.com mailing lists that links the blog post
  * If the issue is particularly time sensitive, this process may be shortened considerably
  * If the issue affects other frameworks or tools in the Python/web ecosystem, they may privately reach out to discuss with appropriate maintainers, and coordinate a united disclosure and resolution together
  * Link to archive of security issues disclosed
  * Who receives advance notification? This list will not be made public and being a user is not sufficient reason to be on the list
    * Operating-system vendors and other distributors
    * Individual package maintainers who have demonstrated a commitment to responding to and responsibly acting on the notifications
    * Other entities who need to be made aware of a pending security issue; typically this will consist of the largest and/or most likely to be severely impacted known users or distributors
  * Requesting notifications
    * If you believe you should receive notifications, can submit an email to team

**Apache Security**
* Apache Security Team exists to provide help and advice to Apache projects on security issues and to provide coordination of the handling of security vulnerabilities
Reporting
* Encouraged to report to a private security mailing list before disclosing in a public forum
* Provides a list of security contacts; possible to encrypt an email
Vulnerability Information
* Published vulnerabilities can usually be found on the project’s web pages
Vulnerability Handling process:
* Reporter reports the vulnerability privately to Apache
* Appropriate project’s security team works privately with the reporter to resolve the vulnerability
* A new release of the Apache product concerned is made that includes the fix
* The vulnerability is publicly announced
Apache Security Guidance for Committers
* Publishing Information
  * Known, published vulnerabilities should be part of the httpd security pages and clearly linked from homepage
  * Security vulnerabilities should not be entered into a public bug tracker, unless configuration is in place to limit access to the issue to only the reporter and project team
  * Security Mailing Lists – projects may create a specific security mailing list; only a subset of project PMC members and committers will be subscribed
  * Vulnerability Handling (can be adapted, but needs to be documented publicly)
  * Note: no info should be made public about the vulnerability until it is formally announced
  * The reporter reports the vulnerability privately
  * Messages that do not relate to the reporting or managing of an undisclosed security vulnerability in Apache software are ignored and no further action is required
  * If reported to security@apache.org, the security team will forward the report (without acknowledging it) to the project’s security list or private mailing list
  * The project team sends an email to the reporter to acknowledge the report
  * The project team investigates the report and either rejects or accepts it
  * If rejected, the team writes to the reporter to explain why
  * If accepted, the team writes to the reporter to let them know it is accepted and they are working on a fix
  * The project team requests a CVE number from Apache by sending an email and providing a description of the vulnerability (guidance is available to determine if a report requires multiple CVEs or if multiple reports should be merged under one CVE)
  * The project team agrees the fix on their private list
  * The project team provides the reporter with a copy of the fix and a draft vulnerability announcement for comment
  * The project team agrees on the fix, the announcement and the release schedule with the reporter.

**Resources**
[Open Source Software Security Risks and Best Practices](https://cloudacademy.com/blog/open-source-software-security-risks-and-best-practices/) by Cloud Academy
[Inside the Government’s Open Source Software Conundrum](https://www.nextgov.com/cybersecurity/2019/05/inside-governments-open-source-software-conundrum/157186/) by Nextgov
[Django’s security policies](https://docs.djangoproject.com/en/dev/internals/security/#reporting-security-issues) documentation
[Apache Security](https://www.apache.org/security/) documentation
[Apache Security guidance for committers](https://www.apache.org/security/committers.html) documentation
(https://docs.djangoproject.com/en/2.2/topics/security/) - Security in Django (example)

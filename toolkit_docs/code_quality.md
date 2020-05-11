# Code quality

**Having a good deployment pipeline with tests**
For projects that are deployed in an environment (test, staging or production) it is important to ensure that the quailty of code has been tested thoroughly. Why? Well for starters if your team is constantly contributing new code to a code base, then you will want to test all of those quick small changes. Dependencies, updates to libraries and other elements are all checked and cleared when you use . Today, many of these checks are automated, thereby taking the burden off of the developer and open source code tests do the trick. 

**Resources**

Code quality can be measured by online software services like the following (add an integration to one of the softwares and add a badge):
* [Code Climate](https://codeclimate.com/)
* [Codacy](https://www.codacy.com/)
* [LGTM](https://lgtm.com/)

Code coverage is measuring how much of your code is tested and can be measured by using something like Coveralls.
Build checks can be done using the following:
* [Travis CI](https://travis-ci.org/)
* [CircleCI](https://circleci.com/)
* [AppVeyor](https://www.appveyor.com/)
* [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/)
* [GitHub Actions](https://help.github.com/en/actions)

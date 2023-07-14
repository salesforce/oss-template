*This is a suggested `CONTRIBUTING.md` file template for use by open sourced Salesforce projects. The main goal of this file is to make clear the intents and expectations that end-users may have regarding this project and how/if to engage with it. Adjust as needed and remove this paragraph before committing to your repo.*

# Contributing to < *NAME OF PROJECT* >

This page lists the operational governance model of this project, as well as the recommendations and requirements for how to best contribute to < *PROJECT* >. We strive to obey these as best as possible. As always, thanks for contributing – we hope these guidelines make it easier and shed some light on our approach and processes.

# Governance Model
< Pick the most appropriate one >
## Community Based

The intent and goal of open sourcing this project is to increase the contributor and user base. The governance model is one where new project leads (`admins`) will be added to the project based on their contributions and efforts, a so-called "do-acracy" or "meritocracy" similar to that used by all Apache Software Foundation projects.

< or >
## Salesforce Sponsored

The intent and goal of open sourcing this project is to increase the contributor and user base. However, only Salesforce employees will be given `admin` rights and will be the final arbitrars of what contributions are accepted or not.

< or >

## Published but not supported

The intent and goal of open sourcing this project is because it may contain useful or interesting code/concepts that we wish to share with the larger open source community. Although occasional work may be done on it, we will not be looking for or soliciting contributions.

# Getting started

Please join the community on < *Here list Slack channels, Email lists, Glitter, Discord, etc... links* >. Also please make sure to take a look at the project [roadmap](ROADMAP.md) to see where are headed.

# Issues, requests & ideas

Use GitHub Issues page to submit issues, enhancement requests and discuss ideas.

# Contributing

1. **Ensure the bug/feature was not already reported** by searching on GitHub under Issues.  If none exists, create a new issue so that other contributors can keep track of what you are trying to add/fix and offer suggestions (or let you know if there is already an effort in progress).
3. **Clone** the forked repo to your machine.
4. **Commit** changes to your own branch.
5. **Push** your work back up to your fork.
6. **Submit** a Pull Request against the `main` branch and refer to the issue(s) you are fixing. Try not to pollute your pull request with unintended changes. Keep it simple and small.
7. **Sign** the Salesforce CLA (you will be prompted to do so when submitting the Pull Request)

> **NOTE**: Be sure to [sync your fork](https://help.github.com/articles/syncing-a-fork/) before making a pull request.

# Contribution Checklist

- [x] Clean, simple, well styled code
- [x] Comments
  - Module-level & function-level comments.
  - Comments on complex blocks of code or algorithms (include references to sources).
- [x] Tests
  - Increase code coverage, not versa.
  - Use our testkit that contains a bunch of testing facilities you would need. Simply `import com.salesforce.op.test._` and borrow inspiration from existing tests.
- [x] Dependencies
  - Minimize number of dependencies.
  - Prefer Apache 2.0, BSD3, MIT, ISC and MPL licenses.

# Code of Conduct
Please follow our [Code of Conduct](CODE_OF_CONDUCT.md).

# License
By contributing your code, you agree to license your contribution under the terms of our project [LICENSE](LICENSE.txt) and to sign the [Salesforce CLA](https://cla.salesforce.com/sign-cla)

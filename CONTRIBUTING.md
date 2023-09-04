# Contributing

When contributing a major change to this repository, please first discuss the
change you wish to make via an [issue](contributing/ISSUES.md) or via
[Slack in the #racial-justice-legit-info 
channel](https://callforcode.slack.com/archives/C01CRAN53CM) in the [Call for
Code Slack workspace](https://callforcode.org/slack). Minor issues can simply
be addressed by sending by a pull request.

All [pull requests](contributing/PULL-REQUESTS.md) will require you to ensure
the change is certified via the [Developer Certificate of Origin 
(DCO)](https://github.com/apps/dco/). The DCO is a lightweight way for 
contributors to certify that they wrote or otherwise have the right to submit
the code they are contributing to the project.

Please note we have a [Code of Conduct](#code-of-conduct), please follow it in
all your interactions with the project and its community.

## Coding Standards

This project adheres to the PEP 8 Python Coding Style Guidelines, Django naming
conventions, and other standards.  See [STYLE.md](docs/STYLE.md) for details.

## Programming Languages

Scripts are written for "bash" shell.
Python code is written at the [Python 3.6](https://docs.python.org/3.6/) level.

## Managing Dependencies

Install or uninstall all dependencies using these commands while you are
in the pipenv shell:

```console
(cfc) $ pipenv install <program>"
(cfc) $ pipenv lock -r > requirements.txt"
```

The pipfile, pipfile.lock and requirements.txt will be part of the git
commit/pull-request to be reviewed.


## Pull Request Process

1. Fork the repository.
2. Commit your changes to your fork.
3. Submit a pull request. _Don't forget to add yourself in the [Authors](Authors) file!_
4. Handle any feedback before the request is merged.
5. Accept our sincere Thank You!

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, 
body size, disability, ethnicity, gender identity and expression, level of 
experience, nationality, personal appearance, race, religion, or sexual 
identity and orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team on [Slack in the #racial-justice-legit-info channel](https://callforcode.slack.com/archives/C01CRAN53CM). 

All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances. The project team is obligated to maintain confidentiality with regard to the reporter of an incident.Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4, available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/



# Contributing to OpenEEW

OpenEEW is an open source project and we are always happy to receive contributions from our community. You can contribute in different ways:

- Writing tutorials and blog posts
- Improving the documentation
- Submitting bug reports and feature requests
- Forking this repository and submitting a pull request
- Hosting a seismic sensor to expand the network (send us an email at [hello@openeew.com](mailto:hello@openeew.com))

Please read our [contributing guide](https://github.com/openeew/openeew/wiki/Getting-Involved) here.

## Technical Steering Committee (TSC)

The TSC will be responsible for all technical oversight of the OpenEEW project. Participation in the Project through becoming a Contributor and Committer is open to anyone.

The TSC may (1) establish work flow procedures for the submission, approval, and closure/archiving of projects, (2) set requirements for the promotion of Contributors to Committer status, as applicable, and (3) amend, adjust, refine and/or eliminate the roles of Contributors, and Committers, and create new roles, and publicly document any TSC roles, as it sees fit.

### Responsibilities

The TSC will be responsible for all aspects of oversight relating to the Project, which may include:

- Coordinating the technical direction of the Project.
- Approving project or system proposals (including, but not limited to, incubation, deprecation, and changes to a sub-project’s scope).
- Organizing sub-projects and removing sub-projects.
- Creating sub-committees or working groups to focus on cross-project technical issues and requirements.
- Appointing representatives to work with other open source or open standards communities.
- Establishing community norms, workflows, issuing releases, and security issue reporting policies.
- Approving and implementing policies and processes for contributing.

The TSC voting members are initially the Project’s Committers. At the inception of the project, the Committers of the Project will be as set forth within the CONTRIBUTING file within the Project’s code repository. The TSC may choose an alternative approach for determining the voting members of the TSC, and any such alternative approach will be documented in this CONTRIBUTING file. Any meetings of the Technical Steering Committee are intended to be open to the public, and can be conducted electronically, via teleconference, or in person.

### TSC Voting

While the Project aims to operate as a consensus-based community, if any TSC decision requires a vote to move the Project forward, the voting members of the TSC will vote on a one vote per voting member basis.

Quorum for TSC meetings requires at least fifty percent of all voting members of the TSC to be present. The TSC may continue to meet if quorum is not met but will be prevented from making any decisions at the meeting.



# Contributing to Atom

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to Atom and its packages, which are hosted in the [Atom Organization](https://github.com/atom) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[I don't want to read this whole thing, I just have a question!!!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [Atom and Packages](#atom-and-packages)
  * [Atom Design Decisions](#design-decisions)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [JavaScript Styleguide](#javascript-styleguide)
  * [CoffeeScript Styleguide](#coffeescript-styleguide)
  * [Specs Styleguide](#specs-styleguide)
  * [Documentation Styleguide](#documentation-styleguide)

[Additional Notes](#additional-notes)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## Code of Conduct

This project and everyone participating in it is governed by the [Atom Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [atom@github.com](mailto:atom@github.com).

### Atom and Packages

Atom is a large open source project &mdash; it's made up of over [200 repositories](https://github.com/atom). When you initially consider contributing to Atom, you might be unsure about which of those 200 repositories implements the functionality you want to change or report a bug for. This section should help you with that.

Atom is intentionally very modular. Nearly every non-editor UI element you interact with comes from a package, even fundamental things like tabs and the status-bar. These packages are packages in the same way that packages in the [Atom package repository](https://atom.io/packages) are packages, with one difference: they are bundled into the [default distribution](https://github.com/atom/atom/blob/10b8de6fc499a7def9b072739486e68530d67ab4/package.json#L58).

<a id="atom-packages-image"/>

![atom-packages](https://cloud.githubusercontent.com/assets/69169/10472281/84fc9792-71d3-11e5-9fd1-19da717df079.png)

To get a sense for the packages that are bundled with Atom, you can go to `Settings` > `Packages` within Atom and take a look at the Core Packages section.

Here's a list of the big ones:

* [atom/atom](https://github.com/atom/atom) - Atom Core! The core editor component is responsible for basic text editing (e.g. cursors, selections, scrolling), text indentation, wrapping, and folding, text rendering, editor rendering, file system operations (e.g. saving), and installation and auto-updating. You should also use this repository for feedback related to the [Atom API](https://atom.io/docs/api/latest) and for large, overarching design proposals.
* [tree-view](https://github.com/atom/tree-view) - file and directory listing on the left of the UI.
* [fuzzy-finder](https://github.com/atom/fuzzy-finder) - the quick file opener.
* [find-and-replace](https://github.com/atom/find-and-replace) - all search and replace functionality.
* [tabs](https://github.com/atom/tabs) - the tabs for open editors at the top of the UI.
* [status-bar](https://github.com/atom/status-bar) - the status bar at the bottom of the UI.
* [markdown-preview](https://github.com/atom/markdown-preview) - the rendered markdown pane item.
* [settings-view](https://github.com/atom/settings-view) - the settings UI pane item.
* [autocomplete-plus](https://github.com/atom/autocomplete-plus) - autocompletions shown while typing. Some languages have additional packages for autocompletion functionality, such as [autocomplete-html](https://github.com/atom/autocomplete-html).
* [git-diff](https://github.com/atom/git-diff) - Git change indicators shown in the editor's gutter.
* [language-javascript](https://github.com/atom/language-javascript) - all bundled languages are packages too, and each one has a separate package `language-[name]`. Use these for feedback on syntax highlighting issues that only appear for a specific language.
* [one-dark-ui](https://github.com/atom/one-dark-ui) - the default UI styling for anything but the text editor. UI theme packages (i.e. packages with a `-ui` suffix) provide only styling and it's possible that a bundled package is responsible for a UI issue. There are other bundled UI themes, such as [one-light-ui](https://github.com/atom/one-light-ui).
* [one-dark-syntax](https://github.com/atom/one-dark-syntax) - the default syntax highlighting styles applied for all languages. There are other bundled syntax themes, such as [solarized-dark-syntax](https://github.com/atom/solarized-dark-syntax). You should use these packages for reporting issues that appear in many languages, but disappear if you change to another syntax theme.
* [apm](https://github.com/atom/apm) - the `apm` command line tool (Atom Package Manager). You should use this repository for any contributions related to the `apm` tool and for publishing packages.
* [atom.io](https://github.com/atom/atom.io) - the repository for feedback on the [Atom.io website](https://atom.io) and the [Atom.io package API](https://github.com/atom/atom/blob/master/docs/apm-rest-api.md) used by [apm](https://github.com/atom/apm).



## How to contribute to Ruby on Rails

#### **Did you find a bug?**

* **Do not open up a GitHub issue if the bug is a security vulnerability
  in Rails**, and instead to refer to our [security policy](https://rubyonrails.org/security).

* **Ensure the bug was not already reported** by searching on GitHub under [Issues](https://github.com/rails/rails/issues).

* If you're unable to find an open issue addressing the problem, [open a new one](https://github.com/rails/rails/issues/new). Be sure to include a **title and clear description**, as much relevant information as possible, and a **code sample** or an **executable test case** demonstrating the expected behavior that is not occurring.

* If possible, use the relevant bug report templates to create the issue. Simply copy the content of the appropriate template into a .rb file, make the necessary changes to demonstrate the issue, and **paste the content into the issue description**:
  * [**Active Record** (models, database) issues](https://github.com/rails/rails/blob/main/guides/bug_report_templates/active_record_main.rb)
  * [**Action Pack** (controllers, routing) issues](https://github.com/rails/rails/blob/main/guides/bug_report_templates/action_controller_main.rb)
  * [**Generic template** for other issues](https://github.com/rails/rails/blob/main/guides/bug_report_templates/generic_main.rb)

* For more detailed information on submitting a bug report and creating an issue, visit our [reporting guidelines](https://edgeguides.rubyonrails.org/contributing_to_ruby_on_rails.html#reporting-an-issue).

#### **Did you write a patch that fixes a bug?**

* Open a new GitHub pull request with the patch.

* Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.

* Before submitting, please read the [Contributing to Ruby on Rails](https://edgeguides.rubyonrails.org/contributing_to_ruby_on_rails.html) guide to know more about coding conventions and benchmarks.

#### **Did you fix whitespace, format code, or make a purely cosmetic patch?**

Changes that are cosmetic in nature and do not add anything substantial to the stability, functionality, or testability of Rails will generally not be accepted (read more about [our rationales behind this decision](https://github.com/rails/rails/pull/13771#issuecomment-32746700)).

#### **Do you intend to add a new feature or change an existing one?**

* Suggest your change in the [rubyonrails-core mailing list](https://discuss.rubyonrails.org/c/rubyonrails-core) and start writing code.

* Do not open an issue on GitHub until you have collected positive feedback about the change. GitHub issues are primarily intended for bug reports and fixes.

* We generally reject changes to Active Support core extensions. Those change should be proposed in the [Ruby issue tracker instead](https://bugs.ruby-lang.org/issues), as we don't want to conflict with future versions of Ruby.

#### **Do you have questions about the source code?**

* Ask any question about how to use Ruby on Rails in the [rubyonrails-talk mailing list](https://discuss.rubyonrails.org/c/rubyonrails-talk).

#### **Do you want to contribute to the Rails documentation?**

* Please read [Contributing to the Rails Documentation](https://edgeguides.rubyonrails.org/contributing_to_ruby_on_rails.html#contributing-to-the-rails-documentation).




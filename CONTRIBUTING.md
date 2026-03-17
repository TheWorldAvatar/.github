The World Avatar is a highly collaborative project that is still under active development, and used to support a number of academic and industy use cases (visible on at [The World Avatar website](https://theworldavatar.io). We’re still working out the kinks to make contributing to this project as easy and transparent as possible, but we’re not quite there yet. Hopefully this document makes the process for contributing clear and answers some questions that you may have.

## Code of Conduct ##

The Organization for Ethical Source has produced the [Contributor Covenant](https://www.contributor-covenant.org/) as its Code of Conduct, and we expect project participants to adhere to it. Please read [the full text](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) so that you can understand what actions will and will not be tolerated.

## Public Development ##

All work on The World Avatar happens directly on [GitHub](https://github.com/cambridge-cares/TheWorldAvatar). Both core team members and external contributors send pull requests which go through the same review process.

## Semantic Versioning ##

The World Avatar project uses semantic versioning when releasing software, packages, and virtual environment images within the ecosystem. We release hotfix versions for critical bugfixes, minor versions for new features or non-essential changes, and major versions for any breaking changes. Learn more about our versioning system on the [Versioning](https://github.com/cambridge-cares/TheWorldAvatar/wiki/Versioning) wiki page.

## Branching Model ##

The World Avatar project uses the [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) branching model for all development. This means that all releases are result of an approved pull request to the `main` branch. Code that lands in `main` must be compatible with the latest stable release. It may contain additional features, but no breaking changes. We should be able to release a new minor version from the tip of `main` at any time.

## Issues ##

The [GitHub Issues](https://github.com/TheWorldAvatar/baselib/issues) system is used to track all bugs and feature requests within The World Avatar project. We keep a close eye on this and try to make it clear when we have an internal fix in progress. Before filing a new task, try to make sure your problem doesn’t already exist.

When filing a new issue, please make sure to include any related error messages, log statements, and reproduction steps.

If you decide to fix an issue, please be sure to check the comment thread in case somebody is already working on a fix. If nobody is working on it at the moment, please leave a comment stating that you intend to work on it so other people don’t accidentally duplicate your effort.

## Proposing a change ##

If you intend to change any core infrastructure of the project, or make any non-trivial changes to the implementation, we recommend [filing an issue](https://github.com/TheWorldAvatar/baselib/issues/new). This lets us reach an agreement on your proposal before you put significant effort into developing it.

If you’re only fixing a minor bug, it’s fine to submit a pull request right away but we still recommend to file an issue detailing what you’re fixing. This is helpful in case we don’t accept that specific fix but want to keep track of the issue.

## Sending a pull request ##

If you're working on your first pull request, you can learn how from this [free video series](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github).

The core team is monitoring for pull requests. We will review your pull request and either merge it, request changes to it, or close it with an explanation. For critical infrastructure changes we may need to update external tools using The World Avatar, which may cause a delay; we’ll do our best to provide updates and feedback throughout the process.

Before submitting the pull request, please ensure the following is done:

* Ensure the PR name (briefly) describes the change (e.g. "fix-help-text-typo")
* Add a comprehensive description detailing the change
  * Where applicable, also list the potential effects on other areas of the code
* Link to any related issues
* If you've fixed a bug or added code that should be tested, please add tests
* Add appropriate labels and projects
* If non-automated unit tests are present, run them
* Ensure that the source branch has had `main` merged into it 


## Get in touch ##

To get in touch with any of the core contributors (CARES, CoMo, CMCL, or CMPG), please use the [Contact](https://theworldavatar.io/contact-us) page from The World Avatar website.


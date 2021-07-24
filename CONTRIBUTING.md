# Contributing

We love your input! We want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

## We Develop with Github
We use GitHub to host code, to track issues and feature requests, and to accept Pull Requests.

## Report Bugs using Github's [issues](https://github.com/briandk/transcriptase-atom/issues)

If you find bugs, mistakes, or inconsistencies in this project's code or documents, please let us know by [opening a new issue](./issues), but consider searching through existing issues first to check and see if the problem has already been reported. If it has, it never hurts to add a quick "+1" or "I have this problem too". This helps prioritize the most common problems and requests.

### Write Bug Reports with Detail, Background, and Sample Code

[This is an example](http://stackoverflow.com/q/12488905/180626) of a good bug report by @briandk. Here's [another example from craig.hockenberry](http://www.openradar.me/11905408).

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
  - Be specific!
  - Give sample code if you can. [The stackoverflow bug report](http://stackoverflow.com/q/12488905/180626) includes sample code that *anyone* with a base R setup can run to reproduce what I was seeing
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

People *love* thorough bug reports. I'm not even kidding.

## Submit Code Changes through Pull Requests

Simple Pull Requests to fix typos, to document, or to fix small bugs are always welcome.

We ask that more significant improvements to the project be first proposed before anybody starts to code as an [issue](./issues) or as a [draft Pull Request](./pulls), which is a [nice new feature](https://github.blog/2019-02-14-introducing-draft-pull-requests/) that gives other contributors a chance to point you in the right direction, give feedback on the design, and maybe discuss if related work is already under way.

### Use a Consistent Coding Style

* We indent using two spaces (soft tabs)
* We ALWAYS put spaces after list items and method parameters ([1, 2, 3], not [1,2,3]), around operators (x += 1, not x+=1), and around hash arrows.
* This is open-source software. Consider the people who will read your code, and make it look nice for them. It's sort of like driving a car: Perhaps you love doing donuts when you're alone, but with passengers the goal is to make the ride as smooth as possible.

### Use [Github Flow](https://guides.github.com/introduction/flow/index.html) for Pull Requests

We use [Github Flow](https://guides.github.com/introduction/flow/index.html). When you submit Pull Requests, please:

1. Sign the [Contributor License Agreement (CLA.md)](./CLA.md) first.
2. Fork the repo and create your branch from `master`.
3. Add code with [GPG signed commits](https://docs.github.com/en/github/authenticating-to-github/managing-commit-signature-verification/signing-commits).
4. If you've added code that should be tested, add tests.
5. If you've changed APIs, update the documentation.
6. Ensure the test suite passes.
7. Make sure your code lints.
8. Issue that Pull Request!
9. Make sure you've checked the ["allow edit from maintainers" checkbox](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/allowing-changes-to-a-pull-request-branch-created-from-a-fork#enabling-repository-maintainer-permissions-on-existing-pull-requests).

#### Pull Request Reviewing and Editing - Maintainers

The easiest way for repository maintainers to review/edit Pull Request is through [GitHub CLI](https://cli.github.com/). The review/edit flow for maintainers should be:

1. Make sure [GitHub CLI](https://cli.github.com/) is installed locally.
2. Find the PR to be reviewed/edited and run the `gh pr checkout <PR-number>` command locally in the CLI. It will checkout the PR into a new branch locally.
3. Update the Pull Request with signed commits.
4. Run `git push` to send your changes to the upstream PR.

All commits in the PR, from either party, should be signed.

This method will work if PR creator did previous section's step number 9 (which is usually already enabled by default).

### Submit Under the BSD-2-Clause Plus Patent License

In short, when you submit code changes, your submissions are understood to be available under the same [BSD-2-Clause Plus Patent License](./LICENSE.md) that covers the project. We also ask all code contributors to GPG sign the [Contributor License Agreement (CLA.md)](./CLA.md) to protect future users of this project. Feel free to contact the maintainers if that's a concern.

## References

Portions of this CONTRIBUTING.md document were adopted from best practices of a number of open source projects, including:
* [Facebook's Draft](https://github.com/facebook/draft-js/blob/a9316a723f9e918afde44dea68b5f9f39b7d9b00/CONTRIBUTING.md)
* [IPFS Contributing](https://github.com/ipfs/community/blob/master/CONTRIBUTING.md)

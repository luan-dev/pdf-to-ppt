# Contributing

> Contributions are a welcome part of the development process. Please follow the guidelines for contribution

## Pull Request Process

- [ ] Ensure that you are following our [Styling Guide](STYLING.md)
- [ ] Document any changes you have made in the changelog
- [ ] Update the relevant documentation relating to your change
- [ ] Request a review from one of our reviewers

## Branching Strategy

Each branch should contribute a feature or fix. This helps keep the codebase readable and maintainable

We follow a single-slash branch naming convention: `TAG/name`

Here are some example tags:

```
  feat/name: branches that will implement a fully functional feature
  fix/name: branches that fix a big issue
  wip/name: branches that will not be merged any time soon
  test/name: branches that will never be merged
```

The `master` branch is the sole source of truth and should be kept at a stable state

## Semantic Versioning

Package releases shouldn't have to cause issues for the end user

To fix this we use [Semantic Versioning](https://semver.org/): `MAJOR.MINOR.PATCH`

This way we can keep track of minor changes and major changes. End users do not have to worry about breaking changes conflicting with their code

## Commit Messages

Commit often and make short meaningful commit messages. Make sure you are commiting per file and not just adding all to the staging area

We follow [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)

Adding a tag to your commits allow for easier filtering later on. We follow this commit message template: `TAG: message`

Here are some example tags:

```
  feat: add a feature
  fix: fix an issue

  ref: refactoring changes
  doc: documentation updates only
  fmt: formatting changes only (e.g. spacing, line breaks, etc..)
  rep: repo changes only (e.g. changes to git ignore)
  test: changes to testing code only
  task: commits that do not fit in the other categories

  WIP: commits that do not do anything meaningful or just to save progress
```

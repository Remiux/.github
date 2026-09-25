# Contributing to Remiux repositories

This guide applies to every repository in the
[Remiux](https://github.com/Remiux) organization that has no contributing guide
of its own. A repository's own guide takes precedence over this one.

By taking part, you agree to follow the
[Code of Conduct](https://github.com/Remiux/.github/blob/main/CODE_OF_CONDUCT.md).

## Before you start

- **Security issues** do not go in public issues or pull requests. Follow the
  [security policy](https://github.com/Remiux/.github/blob/main/SECURITY.md).
- **Questions** go where [SUPPORT.md](https://github.com/Remiux/.github/blob/main/SUPPORT.md)
  says.
- **Search open and closed issues** before opening a new one.

## Report a bug

Open an issue with the **Bug report** form. Include the version or commit, the
steps to reproduce, what you expected, and what happened. Remove keys, tokens,
and personal data from logs before you paste them.

## Propose a change

Open an issue with the **Feature request** form before a large change. Describe
the problem first, then the change you propose. Agreeing on the scope before
writing code saves work on both sides.

Small fixes — a typo, a broken link, a clear one-line bug — can go straight to
a pull request.

## Open a pull request

1. Fork the repository and create a branch from the default branch.
2. Keep the change focused on one problem. Unrelated changes go in their own
   pull request.
3. Follow the conventions already in the code: naming, formatting, file
   layout, and comment style.
4. Add or update tests when behavior changes.
5. Update the README or docs when usage changes.
6. Run the repository's checks locally. Every pull request runs the checks in
   `.github/workflows/`.
7. Fill in the pull request template and link the issue it resolves.

A maintainer reviews the pull request and may ask for changes. Once the checks
pass and the review is approved, a maintainer merges it.

## Commit messages

Write the subject in the imperative, under 72 characters: *Add retry to the
webhook client*, not *Added retries*. Use the body to explain why the change is
needed when the diff does not make it obvious.

## Secrets and examples

Keys come from the environment, never from the code. Use `example.com` for
domains in examples and an environment variable for every key.

## License

Contributions are made under the license of the repository they go to. See its
`LICENSE` file.

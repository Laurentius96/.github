# Contributing

Thank you for taking the time to look at my work! These guidelines apply to every repository of [Laurentius96](https://github.com/Laurentius96) that does not have its own contributing guide.

## Ways to contribute

- 🐛 **Report a bug or something unclear.** [Open an issue](../../issues/new/choose) with the steps to reproduce it, what you expected and what happened. Screenshots and error messages help a lot.
- 💡 **Suggest an improvement.** Open an issue describing the idea and why it would be useful.
- 📝 **Fix documentation.** Typos, broken links and unclear explanations are welcome fixes.
- 🔧 **Propose a code change.** For anything bigger than a small fix, please open an issue first so we can agree on the approach.

## Pull request workflow

1. Fork the repository and create a branch from `main`:

   ```bash
   git checkout -b fix/short-description
   ```

2. Make your change, keeping it focused on one topic.
3. Check that notebooks and scripts still run from top to bottom, and that the README still matches what the code does.
4. Commit with a clear message (for example, `fix: correct the outlier threshold in the cleaning step`).
5. Open a pull request explaining **what** changed and **why**, and link the related issue.

## Style

- Code, comments, notebooks and documentation in **English**.
- Python: follow [PEP 8](https://peps.python.org/pep-0008/) and keep names descriptive.
- Notebooks: run them end to end before committing, so the saved outputs match the code.
- Never commit credentials, tokens or personal data.

## License

Each repository has its own license (most use [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)). By contributing, you agree that your contribution is shared under the license of the repository you contribute to.

## Code of Conduct

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

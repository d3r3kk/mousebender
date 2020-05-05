# Contributing to mousebender

We welcome contributions to this project! All contributions are welcome, including
activities such as raising issues, submitting patches, or updating our documentation.

## Setup for contributing code/documentation

_For the impatient among us, and as a quick refresher!_

1. Install `poetry` using [the appropriate setup for your OS][install-poetry-link].
1. Sync to this repo, and cd to it.

   ```bash
   git clone https://github.com/brettcannon/mousebender
   cd mousebender
   ```

1. Using `poetry`, install the dependencies for the project.

   ```bash
   poetry install
   ```

1. As a baseline, ensure tests are running.

   ```bash
   poetry run pytest --cov
   ```

1. If you don't have an issue # to work from, please obtain one _before_ starting.
1. Set about creating your change.
1. Be sure to test often.

   ```bash
   poetry run pytest --cov
   ```

   > Note: We use pytest --cov to ensure a base level of test coverage.

1. Submit a PR once you are done, be sure to reference your # issue in the PR.

[install-poetry-link]: https://python-poetry.org/docs/#installation
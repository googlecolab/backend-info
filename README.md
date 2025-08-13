# Backend Information

This repository contains the latest apt-list.txt and pip-freeze.txt files.

## Note

Be aware that these files do not necessarily reflect the current state of the
production environment, but rather the state as of the most recent submitted
changes. There may be a one or two day delay to see the changes in Colab
runtimes.

## Colab’s Past Runtime Version: 2025.07

As explained in [Colab's Runtime Version FAQ](https://research.google.com/colaboratory/runtime-version-faq.html),
Colab will make certain past runtime versions available for users to select.
The specific runtime version "2025.07" contains the following components:

- Ubuntu 22.04 LTS
- Python 3.11
  - numpy 2.0.2
  - PyTorch 2.6.0
  - Jax 0.5.2
  - Tensorflow 2.18.0 (not included in TPU runtimes)
- R version 4.5.1 (2025-06-13) -- "Great Square Root"
- julia version 1.10.9

For the exact details of installed OS & Python packages and versions, refer to the
individual `*.txt` files in this repo.

## Contributing

If you have a problem, or see something that could be improved, please
[file an issue](https://github.com/googlecolab/colabtools/issues). However, we
don't have the bandwidth to support review of external contributions, and we
don't want user PRs to languish, so we aren't accepting any external
contributions right now.

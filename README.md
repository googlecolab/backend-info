# Backend Information

This repository contains the latest apt-list.txt and pip-freeze.txt files.

## Note

Be aware that these files do not necessarily reflect the current state of the
production environment, but rather the state as of the most recent submitted
changes. There may be a one or two day delay to see the changes in Colab
runtimes.

## Colab's Past Runtime Versions

Colab now supports pinning a notebook to one of several past runtime versions,
which can be desirable for more consistent notebook execution results. More
information about this feature is available at the
[blog post](https://developers.googleblog.com/en/google-colab-adds-more-back-to-school-improvements/)
and the
[FAQ](https://research.google.com/colaboratory/runtime-version-faq.html).
Currently available past runtime versions are as follows:

### 2026.01

*   Ubuntu 22.04.5 LTS
*   Python 3.12.12
*   numpy 2.0.2
*   PyTorch 2.9.0
*   Jax 0.7.2
*   TensorFlow 2.19.0 (not included in TPU runtimes)
*   R version 4.5.2 (2025-10-31) -- "[Not] Part in a Rumble"
*   julia version 1.11.5

For the exact details of installed OS & Python packages and versions, refer to
the individual `*.txt` files at this
[GitHub commit](https://github.com/googlecolab/backend-info/tree/bd8aaa4580401a7fbf96a52fab5a7acf96f50b73.).

### 2025.10

*   Ubuntu 22.04.4 LTS
*   Python 3.12.12
*   numpy 2.0.2
*   PyTorch 2.8.0
*   Jax 0.5.3
*   TensorFlow 2.19.0 (not included in TPU runtimes)
*   R version 4.5.1 (2025-06-13) -- "Great Square Root"
*   julia version 1.11.5

For the exact details of installed OS & Python packages and versions, refer to
the individual `*.txt` files at this
[GitHub commit](https://github.com/googlecolab/backend-info/tree/7a0599e3401b4c158fc34a8023e042fa3691be32).

### 2025.07

*   Ubuntu 22.04.04 LTS
*   Python 3.11.13
*   numpy 2.0.2
*   PyTorch 2.6.0
*   Jax 0.5.2
*   Tensorflow 2.18.0 (not included in TPU runtimes)
*   R version 4.5.1 (2025-06-13) -- "Great Square Root"
*   julia version 1.10.9

For the exact details of installed OS & Python packages and versions, refer to
the individual `*.txt` files at this
[GitHub commit](https://github.com/googlecolab/backend-info/tree/ef1cba030a9f7a39bf42912a42f6462d6d4908e8).

## Contributing

If you have a problem, or see something that could be improved, please
[file an issue](https://github.com/googlecolab/colabtools/issues). However, we
don't have the bandwidth to support review of external contributions, and we
don't want user PRs to languish, so we aren't accepting any external
contributions right now.

# Backend Information

This repository contains the latest apt-list.txt and pip-freeze.txt files.

## Note

Be aware that these files do not necessarily reflect the current state of the
production environment, but rather the state as of the most recent submitted
changes. There may be a one or two day delay to see the changes in Colab
runtimes.

## Colab’s Fallback Runtime Version

When performing a large upgrade of the runtime, Colab temporarily makes
available a fallback runtime version representing a version of the runtime prior
to the upgrade. The purpose of the fallback runtime version is to provide users
a mechanism to more smoothly upgrade their notebooks to ensure they continue to
work with Colab’s current runtime version. The fallback runtime version is
available from the Command Palette via the "Use fallback runtime version"
command when connected to a runtime. Of note, this setting does not persist
across sessions – the command will need to be invoked on each new session.

## Contributing

If you have a problem, or see something that could be improved, please
[file an issue](https://github.com/googlecolab/colabtools/issues). However, we
don't have the bandwidth to support review of external contributions, and we
don't want user PRs to languish, so we aren't accepting any external
contributions right now.

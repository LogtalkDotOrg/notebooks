# Logtalk Jupyter notebooks

If you're new to Jupyter notebooks, start by opening and playing with the
`JupyterKernelForLogtalkOverview.ipynb` notebook. If you're new to Logtalk,
start with the `LogtalkTutorial.ipynb` notebook.

Don't restrict yourself to the provided notebooks. Create your own. Binder
allows you to save and share the notebooks you create.

## Jupyter kernel

- Repo: https://github.com/LogtalkDotOrg/logtalk-jupyter-kernel
- Package: https://pypi.org/project/logtalk-jupyter-kernel/

## Supported Prolog backends

Online at https://mybinder.org you can currently use:

- GNU Prolog 1.6.0
- SWI-Prolog 9.1.15 (default)
- Trealla Prolog 2.27.27

Local installation of the kernel supports several other Prolog backends. See
the kernel repo for details. Limitations in the Docker images used by Binder
currently prevent installing other Prolog backends supported by the kernel.

## Switching between backends

1. Add a code cell at the top of a notebook.
2. Type `gnu.` to switch to GNU Prolog, `swi.` to switch to SWI-Prolog (but
this is the default backend), or `trealla.` to switch to Trealla Prolog.
3. Select the cell and execute it (by typing, by default, Shift-Enter).

## Contributions

Contributions are most welcome. Open issues or create merge requests in the
https://github.com/LogtalkDotOrg/notebooks repo.

## Prolog notebooks

You can also create, play, and share Prolog notebooks using your own URL.
Taking into account that the Binder support files are work-in-progress:

1. Create a git repo for your notebooks.
2. Visit the https://github.com/LogtalkDotOrg/notebooks repo and copy the
contents of the `binder` directory to your own repo.
3. Add a `README.md` file and your notebooks.
4. Visit https://mybinder.org and follow the instructions there.

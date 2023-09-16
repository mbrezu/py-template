# Python Template

This is a very basic template for a new Python project.
It's supposed to save time when creating new applications.

What it gives you:

 * `init.sh` - script to initialize a virtual environment,
 * `source activate.sh` - script to activate the virtual environment (will look for and source `activate`),
 * `install.sh` and `requirements.txt` - script to download the required packages,
 * a `run.sh` script and
 * a `.gitignore` file.

How to use it:

1. `degit mbrezu/py-template <my-new-project-folder>`
2. `./init.sh`
3. `source activate.sh`
4. `./install.sh`
5. `./run.sh`

TODO:
- a bare bones `Dockerfile`
- an interactive script
  - that deletes itself afterwards
  - and adds/suggests requirements
  - and maybe selects a different `src/main.py`

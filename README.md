## Setting up your local environment

First clone the repository to your local machine

```bash
git clone git@github.com:hemantharajMunusamy/data_science_projects.git
```

Then make a virtual environment using `uv`.

If you don't have `uv` on your system, first install it following the [instruction here](https://docs.astral.sh/uv/getting-started/installation/).

Then build the environment using
```bash
uv sync
```

Then to activate the environment, run
```bash
source .venv/bin/activate
```
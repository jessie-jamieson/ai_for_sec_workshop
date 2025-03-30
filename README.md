### Environment Setup
1. This repository consists of collection of Jupyter notebooks and Python files that will walk you through different applications of data/AI skills in security

2. The authors have tested this in the following environments
- VS Code 1.98.2 on a MacOS 15.3.2


**INSTRUCTIONS**
1. Install uv (uv manages python versions, packages and dependencies)
a. Follow your preferred method of installation [here](https://docs.astral.sh/uv/getting-started/installation/). We recommend Homebrew installs on Mac
b. Run `uv python list` and note this output. This will be used later. 
c. Add the following to your login shell settings (Ex: ~/.bash_profile on Mac)
```
eval "$(uv generate-shell-completion bash)"
export PATH="$PATH:<your output from step 1b>" (It should look something like: export PATH="$PATH:$HOME/path/to/uv/python/cpython-3.10.16-macos-aarch64-none/bin/")
export UV_PYTHON_PREFERENCE="only-managed"
```

2. Git clone this repository by running:  `git clone git@github.com:AI-and-Security/ai_for_sec_workshop.git`

3. Inside the repository, run the command to test your environment. The output is self-explanatory
`uv run test.py` 
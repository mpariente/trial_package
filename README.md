# trial_package
Trial package to test relative imports before running setup.py

## Why this repo?
So I had some trouble understanding in which case relative imports are working or not, so I made a repo for it. It will evolve as long as I understand more things on the subject.

## How do relative imports work?

- Say you cloned the repo, you obtain a folder like this ![folder strucure][fold]

- If you want to run core.py, you can run it from the path ~/trial_package/ with
`python -m trial_package.core ` (the option -m is here to run library module as a script)
- However, if you try from ~/trial_package/trial_package/, neither `python -m core` and `python core.py`


[fold]: https://github.com/mpariente/trial_package/folder_structure.png "fold"

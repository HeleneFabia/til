# TIL - Today I Learned

## Command Line

- copy the output of a command: `... | yank`
- interactively explore a folder's content: `ncdu foldername`
- filter the output of a command in a regex-like way: `... | grep -i ...` (`-i` stands for case insensitive)
- get current processes of a localhost and kill it via PID: `sudo lsof -i :8008` and `sudo kill -9 PID`
- print first 10 lines of a text file: `head -10 file.txt`

## Git
- save and apply stash by name: `git stash push -m stashname` and `git stash apply stash^{/stashname}`

## Python
### Pytest
- collect all tests and find bugs in your test scripts: `pytest --collect-only`

## About
At my job and during side projects, I constantly learn new things. This is my collection of them.

Props to [thoughtbot/til](https://github.com/thoughtbot/til) for the original idea.


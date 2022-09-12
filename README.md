# TIL - Today I Learned

## Command Line

- `... | yank` → copy the output of a command
- `ncdu foldername` → interactively explore a folder's content
- `... | grep -i ...` → filter the output of a command in a regex-like way (`-i` stands for case insensitive)
- `sudo lsof -i :8008` → and `sudo kill -9 PID` get current processes of a localhost and kill it via PID
- `head -10 file.txt` → print first 10 lines of a text file
- `scp -rp remote_server_name@ip_address:path/to/dir path/to/local/dir` → copy directory with contents from remote machine to local machine
- `ls my_dir | wc -l` → count number of files in `my_dir`
- `find /home/username/ -name "*.err”` → find a file via its name

## Git
- `git stash push -m stashname` and `git stash apply stash^{/stashname}` → save and apply a stash

## Python
### Pytest
- `pytest --collect-only` → collect all tests and find bugs in your test scripts
### Other
- `shutil.rmtree()` → remove directory and its contents

## About
At my job and during side projects, I constantly learn new things. This is my collection of them.

Props to [thoughtbot/til](https://github.com/thoughtbot/til) for the original idea.

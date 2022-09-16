# Today I Learned (2022–ongoing)

## Command Line

- copy the output of a command → `... | yank` 
- interactively explore a folder's content → `ncdu foldername` 
- filter the output of a command in a regex-like way (`-i` stands for case insensitive) → `... | grep -i ...` 
- get current processes of a localhost and kill it via PID → `sudo lsof -i :8008` → and `sudo kill -9 PID` 
- print first 10 lines of a text file → `head -10 file.txt`
- copy directory with contents from remote machine to local machine → `scp -rp remote_server_name@ip_address:path/to/dir path/to/local/dir` 
- count number of files in `my_dir` → `ls my_dir | wc -l` 
- find a file via its name → `find /home/username/ -name "*.err”`

## Git
- save and apply a stash by name → `git stash push -m stashname` `git stash apply stash^{/stashname}`

## Python
### Pytest
- collect all tests and find bugs in your test scripts → `pytest --collect-only`
### PyTorch
- ensure reproducible results →
`g = torch.Generator().manual_seed(4567)` `torch.rand(3, generator=g)`
### Other
- remove directory and its contents → `shutil.rmtree()` 
- wrapping a string in a list returns a list of all characters → `list(“my_string”)` becomes `[”m”, “y”, “_”, “s”, “t”, “r”, “i”, “n”, “g”]`
- instead of getting a KeyError when a certain key is not in a dictionary when calling `my_dict[my_key]`, define a default value to be returned → `my_dict.get(my_key, default_value)`
- print variable name and value → `print(f”{my_var}=”)`
- sort a dictionary by value in ascending/descending order → `sorted(my_dict.items(), key=lambda kv: kv[1])`/`sorted(my_dict.items(), key=lambda kv: kv[-1])`  

## About
At my job and during side projects, I constantly learn new things. This is my collection of them.

Props to [thoughtbot/til](https://github.com/thoughtbot/til) for the original idea.

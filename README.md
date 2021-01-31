# rdiff

Run a diff between local or remote file. or directory.

## Requirements

- diff
- ssh
- zsh

## Setup

```
$ cat rdiff >> ~/.zshrc
```

## Usage

- Local and remote file
```
$ rdiff test.txt remote_host:test.txt

or

$ rdiff remote_host:test.txt test.txt
```

- Remote and remote file
```
$ rdiff remote_host1:test.txt remote_host2:test.txt
```

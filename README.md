# lawg

A bash script that saves timestamped console output.

## Installation

Save script to somewhere in your `$PATH`.

## Usage

```bash
cat /lots/of/output | lawg output-name
```

`lawg` allows you to run the same command many times while saving all the console output to a directory with your `output-name` namespace. 
Each file generated is timestamped.

By default, the output is put in your `/tmp` directory. That can be modified by providing an alternate directory path with the `-d` flag:

```bash
cat /lots/of/output | lawg output-name -d ~/Documents
```

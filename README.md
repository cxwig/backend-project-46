### Tests and status:
[![Actions Status](https://github.com/deletevochrome/backend-project-46/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/deletevochrome/backend-project-46/actions)
[![Maintainability](https://api.codeclimate.com/v1/badges/e220e2f6ff6355daf7f9/maintainability)](https://codeclimate.com/github/deletevochrome/backend-project-46/maintainability)

### Difference Calculator:

Difference Calculator is a command-line utility that compares two configuration files and outputs the differences between them in various formats.
It supports JSON and YAML file types and can display results in stylish, plain, or JSON format.

This project was developed as part of a backend learning project to practice CLI tools, Node.js modules, and automated testing.

```
Usage: gendiff [options] <filepath1> <filepath2>                                                                                                                                ✔ 

Compares two configuration files and shows a difference.

Options:
  -V, --version        output the version number
  -h, --help           output usage information
  -f, --format <type>  output format

Source files types:
  - json
  - yml (yaml)
  
Diff formatting types:
  - stylish (default)
  - plain
  - json
  
Usage example:
  gendiff ./__fixtures__/file1.json ./__fixtures__/file2.json -f json

```
### Instalation:
```
1. git clone git@github.com:deletevochrome/backend-project-46.git
2. make install
```

### Run automated tests:

```make test
```
```Technologies

Node.js

Commander.js

Jest

Eslint```

### Difference generator

#### About the project

The project implements a utility to find differences in configuration files.  
Utility Features:  
- support for different formats - json, yaml.
- generate report in three different views.

#### Getting started

```
$ gendiff --help
Usage: gendiff [options] <filepath1> <filepath2>

Compares two configuration files and shows a difference.

Options:
  -V, --version        output the version number
  -f, --format [type]  output format (default: "stylish")
  -h, --help           output usage information
```

#### Example of comparing JSON files. Formatter: 'stylish':
[![asciicast](https://asciinema.org/a/459767.svg)](https://asciinema.org/a/459767)

#### Example of comparing YAML files. Formatter: 'stylish':
[![asciicast](https://asciinema.org/a/459768.svg)](https://asciinema.org/a/459768)

#### Example of comparing JSON and YAML files. Formatter: 'plain':
[![asciicast](https://asciinema.org/a/459967.svg)](https://asciinema.org/a/459967)

#### Example of comparing JSON and YAML files. Formatter: 'json':
[![asciicast](https://asciinema.org/a/460058.svg)](https://asciinema.org/a/460058)

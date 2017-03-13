POSIX Shell Array
=================

[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/Ventto/posix-shell-array/blob/master/LICENSE)
[![Language (Bash)](https://img.shields.io/badge/powered_by-Bash-brightgreen.svg)](https://www.gnu.org/software/bash)

*"This is a POSIX Shell array implementation."*

# Download

```bash
$ wget https://raw.githubusercontent.com/Ventto/posix-shell-array/master/array.sh
```

# How to

* Add the following line to your script:

```bash
. array.sh
```

* Look at `test.sh` as examples.

**Warning:
There is no check on the number of arguments. Prior to respect the API.**

# Functions

```bash
array 'string'
array_add "$elem" "$arr"
array_contains "$elem" "$arr"
array_del "$elem" "$arr"
array_delall "$elem" "$arr"
array_delindex "$index" "$arr"
array_empty "$arr"
array_get "$index" "$arr"
array_head "$arr"
array_indexof "$elem" "$arr"
array_last "$arr"
array_len "$arr"
array_map "$func" "$arr"
array_occur "$elem" "$arr"
```

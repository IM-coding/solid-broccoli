# This is simple package for time formats converting

To install a wheel from PyPI:
`pip install solid-broccoli`

## To convert unix timestamp (s or ms) to human-readable format run in your command line

`solid-broccoli -u 1681156492`
or
`python -m solid_broccoli -u 1681156492`

Output
`Date: 10-04-2023, 22:54:52`

## To convert human-readable format to unix timestamp run in your command line

`solid-broccoli -d '10-04-2023, 22:54:52'`
or
`python -m solid_broccoli -d '10-04-2023, 22:54:52'`

Output
`Unix timestamp: 1681156492`

NOTE: days first preferred over other formats (i.e. MM-DD-YYYY). Timezone - ignored


```
usage: solid-broccoli [-h] [-u UNIX] [-d DATE]

options:
  -h, --help            show this help message and exit
  -u UNIX, --unix UNIX  Unix timestamp input s/ms.
  -d DATE, --date DATE  Date preferable format - days first (example MM-DD-YYYY). Timezone - ignored.
```

[Github](https://github.com/IM-coding/solid-broccoli)
[PyPI](https://pypi.org/project/solid-broccoli/0.0.1/)
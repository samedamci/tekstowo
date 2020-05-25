# tekstowo

Retrieve lyrics or translation of a given song from
[tekstowo.pl](http://www.tekstowo.pl/).

### Help

```
usage: tekstowo.py [-h] [-t] [-l] [-f FILE] [-q] [-p] song

Find lyrics and translation for a song using tekstowo.pl

positional arguments:
  song                  Song to find lyrics for in format (with quotes): "<ARTIST> - <TITLE>"

optional arguments:
  -h, --help            show this help message and exit
  -t, --translation     Download translation
  -l, --lyrics          Download lyrics
  -f FILE, --file FILE  Save lyrics to file
  -q, --quiete          Do not open pager, without output
  -p, --print           Print output to stdout instead of open pager
```

### Example

```shell
$ ./tekstowo.py "Nirvana - About a girl"
I need an easy friend
I do, with an ear to lend
...
```

### Credits

Most of the code has been copied from
[winamp-tekstowo](https://github.com/asdfMaciej/winamp-tekstowo)
project by [Maciej Kaszkowiak](https://github.com/asdfMaciej). If you like it,
take a look at his projects.

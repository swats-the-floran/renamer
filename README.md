# renamer
simple python renamer which supports regular expressions and has simplest command line interface.

example of usage:
    renamer path=/path/to/dir/ hastext='some text' from='replacing' to='replacement' fdirs=[files|dirs|both]
defaults:
    to=
    hastext=
    fdirs=files
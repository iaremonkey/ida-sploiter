Modified version of IDA Sploiter that also has "hacky" support for
ELF binaries.

To install IDA Sploiter simply copy 'idasploiter.py' to IDA's plugins folder.
The plugin will be automatically loaded the next time you start IDA Pro.
To support parsing of ELF files please install pyelftools via
```> pip install pyelftools``` from https://github.com/eliben/pyelftools

Original plugin and documentation by Peter Kacherginsky <iphelix@thesprawl.org>
can be found at: http://thesprawl.org/projects/ida-sploiter/

Thanks to Peter Kacherginsky for the original plugin, Eli Bendersky for pyelftools
and Dhiru Kholia for porting checksec to python.

IEEE Transactions Conference Paper Preamble
- - -

Usage:

    >> git init new-paper/
    [new-paper] >> git submodule add https://github.com/vbajpai/ieeetran-conf-preamble.git .preamble/

    [new-paper] >> ln -s .preamble/IEEEabrv.bib
    [new-paper] >> ln -s .preamble/IEEEtran.bst
    [new-paper] >> ln -s .preamble/IEEEtran.cls
    [new-paper] >> ln -s .preamble/Makefile

    [new-paper] >> cp .preamble/index.tex .
    [new-paper] >> cp .preamble/index.bib .

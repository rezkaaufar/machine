# commAI

This repository uses the pytorch-seq2seq library developed by IBM as a submodule.
If you clone this repository, run `git submodule update --init --recursive', to download the contents of the submodule.



### ibm-seq2seq on cartesius
from ibm-seq2seq dir:
1. ```pip install --user -r requirements.txt```
2. ```python setup.py  install --user```

on sample.py, first line:
1. ```import sys```
2. ```sys.path.insert(0, '/home/ebruni/.local/lib/python2.7/site-packages/')```
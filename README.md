# The Monic Project

Copyright (C) 2014-2020, Zhe Chen.

This project includes the tool Monic and the dataset of LTL formulas. After unzipping the downloaded file, you can see an executable file "monic" and two textual files which contain the LTL formulas. Note that Monic can only run on Ubuntu Desktop (64-bit) or compatible systems.

To compute two-valued monitorability, one may use the following commands:
```bash
    $ ./monic -c four_valued_examples.txt
    $ ./monic -c ltl_patterns.txt
```

To compute four-valued monitorability, one may use the following commands:
```bash
    $ ./monic -n4 -c four_valued_examples.txt
    $ ./monic -n4 -c ltl_patterns.txt
```
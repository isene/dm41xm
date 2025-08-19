# dm41xm

[![HP-41](https://img.shields.io/badge/HP--41-Calculator-orange)](https://en.wikipedia.org/wiki/HP-41C)
[![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![License](https://img.shields.io/badge/License-Public%20Domain-brightgreen.svg)](https://unlicense.org/)
[![GitHub stars](https://img.shields.io/github/stars/isene/dm41xm.svg)](https://github.com/isene/dm41xm/stargazers)
[![Stay Amazing](https://img.shields.io/badge/Stay-Amazing-blue.svg)](https://isene.org)

<img src="img/dm41x_logo.svg" align="left" width="150" height="150">
<br clear="left"/>

This program is used in conjunction with the DM41X calculator.
For more information about the DM41X, see https://www.swissmicros.com

The program extracts an ASCII XM file from a DM41X state file.

Usage: 41x [options]
    -f, --file DM41X-file            Specify the DM41X file you want to extract from
    -a, --ascii ASCII-file           Specify the XM ASCII file you want to extract
    -h                               Display SHORT help text
        --help                       Display LONG help text

Example: 41x -f mystatefile.d41 -a MYFILE

This would extract the XM ASCII file "MYFILE" from the statefile "mystatefile.d41".

Version: 0.1 (2020-03-27)
License: Public domain


# gendoc
|     key | description
|     ---:|:---
|  script | gendoc - convert inline documentation to man, html or pdf
|    type | bash
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 2.02
| license | GNU General Public License

gendoc is a Bash script that looks for gendoc-formatted documentation in a
script, and converts it to three kinds of documentation:
- a web page; it is placed in a directory html, next to the directory in
which the script resides. So if the script is /local/bin/test, the html
documentation will be /local/html/test.html.
- a pdf document; it is placed in /local/pdf/test.pdf.
- a man page; it is placed in /local/man/man1/test.1.

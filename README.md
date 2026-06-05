# gendoc

convert inline documentation to man, html or pdf

## Properties

|key|value|
|-:|:-|
|  script:|gendoc|
|   short:|convert inline documentation to man, html or pdf|
|    type:|bash|
|  author:|Wybo Dekker|
|   email:|[wybodekker@me.com.](mailto:wybodekker@me.com.)|
| version:|2.05|
| license:|GNU General Public License|
|   intro:|gendoc is a Bash script that looks for gendoc-formatted|
|         |documentation in a /script/. If the argument is an|
|         |absolute path, that path is followed to find the script;|
|         |otherwise it is searched in your PATH; if the search fails,|
|         |the script is supposed to be in the current directory.|
|         |It creates three kinds of documentation for the script:|
|         |- a web page; it is placed in a directory **html**, next to|
|         |the directory in|
|           |which the script resides. So if the script is|
|           |**/local/bin/test**, the html documentation will be|
|           |**/local/html/test.html**.|
|         |- a pdf document; it is placed in **/local/pdf/test.pdf**.|
|         |- a man page; it is placed in **/local/man/man1/test.1**.|

## Options

|option|description|
|:-|:-|
|-h,--help	|print this help and exit|
|-H,--Help	|print full documentation via less and exit|
|-V,--version	|print version and exit|
|-m,--man	|generate a man page|
|-i,--index	|do (re)generate an index in the html directory|
|-p,--pdf	|generate a PDF file|
|-v,--verbose	|print some intermediate messages|
|-w,--web	|generate a web page|

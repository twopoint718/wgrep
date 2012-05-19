wgrep
=====
`web grep` searchs a web page for given regex. It uses
[links(1)](http://linux.die.net/man/1/links) for dumping out only the text of
the page, and then grepping it.

The exit status is the exit status of
[grep(1)](http://linux.die.net/man/1/grep) so you could use this as the basis
for a shell-based browser testing framework. Or at least that's *one* use.

Options
-------
`-c` highlight matches in color

`-h` print a help message and then exit, successfully

`-v` print a version and then exit, successfully

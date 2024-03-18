A CLI tool that searches a text file or a directory containing text files for any mentions of dates, and prints any lines containing dates along with the filename.

Takes two optional arguments.

-p PATH. A path to the file or repository that is to be searched. For example, $ find-dates -p path/to/text/files
-i IGNORE. A comma-separated list of file extensions to ignore. For example, $ find-dates -i .csv,.txt,.py

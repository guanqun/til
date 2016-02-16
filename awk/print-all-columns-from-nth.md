## set the first column to empty and then print all

    awk '{$1=""; print $0}' somefile

## using `cut`

    cat somefile | cut -d\  -f2-

`-d` specifies the delimiter and `-f` specifies the list of columns.


From [stackoverflow](http://stackoverflow.com/questions/2961635/using-awk-to-print-all-columns-from-the-nth-to-the-last)

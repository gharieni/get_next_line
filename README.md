# Get Next Line

**Description:**
* get next line is a function that reads a file or specific fd (STDIN, .. ) line by line
* read from multiple file descriptor without lost the order of the ligne 

```
int get_next_line(const int fd, char **line)
```


**Return value:**
* `return 1 when it read a line`
* `return 0 when it finished reading a file`
* `return -1 when an error occurs`

##
More information can be found on the [PDF].

[PDF]: https://github.com/gharieni/get_next_line/blob/master/get_next_line.en.pdf

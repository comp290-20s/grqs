---
title: GRQ01 - Chapter 2
author: 
- Your-Name Here
geometry: margin=1in
---

Each of these questions assumes you are working in the `learncli` container for `comp290`. The first slide of Lecture 1 provides instructions for how to start this container.

## Chapter 2. Directories, Files, and Paths

_1. Describe a file system *path* to a friend in your own words._

_2. What is the path of the root directory?_

_3. In the path `/usr/share/dict/words` what is the relationship between `share` and `dict`?_

_4. In a path, what is the last string of text (following the final `/`) named? _

_5. In a path, what is the sequence of names and slashes from the start of the string all the way up to the last slash named?_

_6. What is the `dirname` of the path `/usr/include/stdio.h`?_

_7. What is the `basename` of the path `/usr/include/linux/fs.h`?_

_8.1 Is the path `usr/share/dict/words` relative or absolute?_

_8.2. Is the path `./words` relative or absolute?_

_8.3. Is the path `words` relative or absolute?_

_9. How can you quickly determine whether a path is absolute?_

_10. What is the relationship between `cd` and `pwd`?_

_11. What is the absolute path of `bar/baz` relative to the a current working directory of path `/foo`?_

_12. Are absolute and relative paths generally interchangeable? If not, why not? If so, what are the benefits of each?_

_13. Read the manual pages of `mkdir`. One option is the `--parents` or `-p` option. Give an example of its usage that results in two directories being created in a single command, the first a parent of the second._

_14. What does the directory `.git` not appear when you run the command `ls /mnt/learncli`, but it does when you run the command `ls -a /mnt/learncli`? What is the significance of the `-a` flag?_

_15. What is the difference between `.` and `..` relative to your `pwd`?_

_16. How many files in the `comp290` container's `/usr` directory are a descendant of a directory named `bin`? What command did you run to answer this question? Hint: use `find` in conjunction with grep and the regular expression `/bin/`._

_17. Why do you need to be more careful about deleting a file with `rm` at the command-line?_

_18. Read the man page description for the `touch` program. By default, what happens when you touch a `FILE` that does not exist?_

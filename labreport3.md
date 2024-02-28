# Lab Report 3
## Bugs

A failure-inducing input for the buggy program, as a JUnit test and any associated code
```

```

An input that doesn't induce a failure, as a JUnit test and any associated code
```

```

The symptom, as the output of running the tests

![Image]()

The bug, as the before-and-after code change required to fix it
```

```
```

```
Changing ____ fixes the issue because _____.

## Researching Commands
`find`
1) size
```
find -size -1M
.
./911report
./biomed
./government
./government/About_LSC
./government/Alcohol_Problems
./government/Env_Prot_Agen
./government/Gen_Account_Office
./government/Media
./government/Post_Rate_Comm
./plos
```
This will find files or directories that are less than 1 Megabyte, which could be helpful for seeing how many smaller files there are.

source: [linuxize](https://linuxize.com/post/how-to-find-files-in-linux-using-the-command-line/)

```
find -size +2M -size 100M
```
This will find files that are within the range of 2 to 100 Megabytes, which could be useful to see how many files are around a common size.
source: [linuxize](https://linuxize.com/post/how-to-find-files-in-linux-using-the-command-line/)

2) modification date
```
find -mtime 15
./biomed/1471-2334-3-13.txt
./biomed/1471-2334-3-15.txt
./biomed/1471-2334-3-9.txt
... (many more files)
./plos/pmed.0020275.txt
./plos/pmed.0020278.txt
./plos/pmed.0020281.txt
```
This will find files that have been modified within the last 15 days. The command could be useful for finding a particular file that was recently updated.
source: [linuxize](https://linuxize.com/post/how-to-find-files-in-linux-using-the-command-line/)

```
find +10 -daystart
... (many files)
./plos/pmed.0020274.txt
./plos/pmed.0020275.txt
./plos/pmed.0020278.txt
./plos/pmed.0020281.txt
```
This will find files that were modified at least 10 days ago. This could be useful to see which files may need to be revisited for possible updates.
source: [linuxize](https://linuxize.com/post/how-to-find-files-in-linux-using-the-command-line/)

3) ignore case
```
find /i "list"

```
This will display results from the current directory containing "list", ignoring the case.
source: [microsoft](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/find)

```
find /i "return"
```
This will display files from the current directory that have "return", ignoring the case.
source: [microsoft](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/find)

4) 
```

```
sentence or two about what it’s doing and why it’s useful
source: URL or a description of where you found it

```

```
sentence or two about what it’s doing and why it’s useful
source: URL or a description of where you found it

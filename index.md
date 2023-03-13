# **Lab Report 5 - Lab Report 3 in a Different Way!**

## **The `less` command**

### **`less -N`**

The `-N` option of less is used to number the lines and display them at the beginning of each line. This option is useful because the numbered lines makes it easier to identify the specific location of a certain thing that a user may be looking for.  

Example 1:

This example shows how the usage of the `-N` option is useful for files with lots of lines and words because without it, the words and lines begin to look look the same and difficult to differentiate. The lines being numbered allows the user to easily identify where a specific word or phrase is located in a file.

Before: input `less California-History.txt`

![Image](https://github.com/jcaylao/LabReport5/blob/main/2.JPG?raw=true)

After: input `less -N California-History.txt`

![Image](https://github.com/jcaylao/LabReport5/blob/main/1.JPG?raw=true)

Example 2:

This example shows that the `-N` option is useful when used on a directory with a large amount of files. As you can see, scrolling through this may make it difficult for the user to identify the file they are looking for. The lines being numbered makes it easier to identify the files especially when scrolling up and down the list.

Before: input `less berlitz2`

![Image](https://github.com/jcaylao/LabReport5/blob/main/4.JPG?raw=true)

After: input `less -N berlitz2`

![Image](https://github.com/jcaylao/LabReport5/blob/main/3.JPG?raw=true)

### **`less`

## **Sources**
https://phoenixnap.com/kb/less-command-in-linux
https://www.geeksforgeeks.org/less-command-linux-examples/
